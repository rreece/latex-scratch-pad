chicago-latex-template
===============================================================================

A template for a scholarly preprint using Chicago-style bibtex refs. 

authors:

-   Ryan Reece ryan.reece@cern.ch

created: March 13, 2013


Note the Makefile
-------------------------------------------------------------------------------

The Makefile is rather general and could be used outside of this template.

    The mother of all Makefiles for LaTeX
        The Makefile that automatically does what you want for (pdf)latex.
    
    SYNOPSIS
        make [pdf|ps|dvi|dvipdf|mf|clean|distclean|realclean|over|draft]
    
    DESCRIPTION
        Builds virtually any LaTeX document with *no* configuration.
        Supports documents with
    
          1. latex and pdflatex markup and figures
          2. optional index with makeindex
          3. optional bibtex bibliographies
          4. optional feynmf figures
    
        This Makefile will properly build all the above automatically if
        present in your markup.
    
    MAIN TARGETS
        pdf
            Builds a pdf file of the document using pdflatex.
            tex -> pdflatex -> pdf
            
        ps
            Builds a ps file of the document using latex.
            tex -> latex -> dvi -> dvips -> ps


TODOs
-------------------------------------------------------------------------------

-   one
-   two

