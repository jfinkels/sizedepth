# Size-depth tradeoffs for nondeterministic circuits #

This file was last updated on July 8, 2014.

## Downloading ##

The markup is available from GitHub.

    git clone git@github.com:jfinkels/sizedepth

A somewhat recent version of the compiled document should be available at
https://cs-people.bu.edu/jeffreyf/static/pdf/sizedepth.pdf, but I can't
guarantee that that will always be up to date, since I compile and upload it
manually.

## Compilation dependencies ##

Compilation requires `pdflatex`, `biber`, and the following LaTeX packages:

* `amsmath`
* `amsthm`
* `amssymb`
* `babel`
* `biblatex`
* `complexity`
* `csquotes`
* `hyperref`
* `thmtools`

To install these packages on Ubuntu 11.04 through 14.04:

    sudo apt-get install texlive-base texlive-latex-base texlive-latex-extra \
      texlive-science biber

## Compiling ##

To compile the document, run

    pdflatex sizedepth
    biber sizedepth
    pdflatex sizedepth

The output is `sizedepth.pdf`, and can be viewed with any PDF reader.

## Copyright ##

Copyright 2014 Jeffrey Finkelstein.

Both the LaTeX markup and the content of this article are made available under
the terms of the Creative Commons Attribution-ShareAlike 4.0 International
License, https://creativecommons.org/licenses/by-sa/4.0/.

Contact
-------

Jeffrey Finkelstein <jeffreyf@bu.edu>
