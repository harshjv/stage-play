# Stage Play [![Build Status](https://travis-ci.org/harshjv/stage-play.svg)](https://travis-ci.org/harshjv/stage-play)

Stage play script written in LaTeX for Verve Youth Festival


## Download pre-built PDF

Get pre-built PDF from [stage-play/releases](https://github.com/harshjv/stage-play/releases)


# Build PDF

LaTeX package is required to build PDF.


## Install LaTeX

    apt-get install --no-install-recommends texlive-fonts-recommended texlive-latex-extra texlive-fonts-extra texlive-latex-recommended dvipng


## Generate PDF

    mkdir _build && pdflatex -output-directory _build tex/script.tex


Your generated PDF is available at `_build/script.pdf`


# License

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).