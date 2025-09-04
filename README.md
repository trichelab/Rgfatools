[<img src="https://www.bioconductor.org/images/logo/jpg/bioconductor_logo_rgb.jpg" width="200" align="right"/>](https://bioconductor.org/)

_Rgfatools_ is an R/Bioconductor package that provides an interface to the `gfatools` utilities for manipulating GFA (Graph Fragment Alignment) and rGFA 
(reference GFA) formats. More detailed documentation for each format can be had
from [Heng Li's github](https://github.com/lh3/gfatools/blob/master/doc/rGFA.md)
and the resources linked therein.

This package is designed to bring pangenome/genome graph support to Bioconductor
by providing tools and utilities for manipulating genome graph representations. 
It is not a drop-in solution for graph alignment or variant annotation tasks!

At present, it's also unstable. I'm wrapping gfatools in the style of Rsamtools.
