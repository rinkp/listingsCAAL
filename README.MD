# listingsCAAL

Language definitions for use with the [listings](https://ctan.org/tex-archive/macros/latex/contrib/listings/) package. 

## Installation

The package does not have `.dtx` file containing documentation or LaTeX sources. Simply copy the `listingsCAAL.sty` file to your TEXMF root (more specifically, the `tex/latex` or your working directory. For use on [Overleaf](https://www.overleaf.com/read/kxkcvgnwgkbr), upload the file to your Overleaf project.

If you decide to install the package to your TEXMF root, make sure to refresh your TeX filename database. 

## Usage

Both CCS and HML formulas can be used with this package. The syntax is available in the ```caal``` language defined in the package by setting the language to `caal`: `\lstset{language=caal}`.

A style simulating that of the CAAL tool is available as well. For that use the `CAALenhanced` style: `\lstset{style=CAALenhanced}`. This is also done in [the example](example.tex).


## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)