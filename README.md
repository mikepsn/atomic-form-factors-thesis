# relativistic-atomic-form-factors

Atomic Physics Honours Thesis on the Theory and Computation of Relativistic Atomic Form Factors

This repository contains the LaTeX source code for my Physics Honours Thesis into the theory and computation of relativistic atomic form factors which I completed in 1998.

The research involved looking at analytic solutions of the Dirac equation for Hydrogenic atoms interacting with high energy X-rays. 
Although the research started in the analytic space, it soon became obvious that only computational approaches were going to solve the complex equations.
Had I continued with a PhD in the area I would have been looking at extending the work to include multiple atoms in a crystal lattice (e.g. XAFS), 2-electron
atoms like Helium and ultimately multi-electron atoms using Dirac-Hartree-Fock approaches. 

The repository contains the LaTeX source for both the thesis and the final presentation. 

The thesis only need minor changes to the LaTeX source (changing the fancyheadings package to fancyhdr). 
Otherwise it compiled fine using pdflatex after all these years and looks identical to the one I submitted. 

The slides however were more problematic as they used the old (and perhaps no longer used) seminar package.
The source for the slides is called land.tex because they are in landscape mode (I know creative, right?). 
As I didn't really want to redo using the beamer package they were compiled in the old way and then converted to PDF
using the following command line:

    latex land.tex; dvips -t landscape land.dvi; ps2pdf land.ps land.pdf

This is because the seminar package doesn't work with pdflatex. 

Direct links to the thesis and the presentation can be found here:

* [Computing Relativistic Atomic Form Factors (Thesis)(PDF)]()
* [Computing Relativistic Atomic Form Factors (Slides)(PDF)]()
