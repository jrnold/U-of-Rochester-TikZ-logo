# University of Rochester TikZLogos

University of Rochester logos in TikZ for inclusion in LaTeX, especially Beamer presentations.

The tikz files were created by

1. Downloading the eps files from [University of Rochester Creative Services](http://www.rochester.edu/creativeservices/graphicstandards/logo.html).
2. Importing the .eps files into Inkscape.
3. Exporting the image to .pgf using the [inkscape2tikz](http://code.google.com/p/inkscape2tikz/) extension.


To use in LaTeX add the following line to the header,

```latex
\usepackage{tikz}
```

and the following line to import the image,

```latex
\input{UR_4col_v1.tex}
```

See **example.tex** for, well, an example.

Unfortunately, the only way I know how to change the size of the
graphics is to edit the .tex file containing the image and change the
`scale` option of the `tikzpicture` environment.
