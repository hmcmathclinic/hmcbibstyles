This project contains the BibTeX bibliography-style files for use
with Harvey Mudd College's
[thesis](https://github.com/hmcmathematics/hmcthesis-class) and
[Clinic](https://github.com/hmcmathematics/hmcclinic-class) LaTeX
report document classes.


Bibliography Style Files
========================

The `.bst` files are BibTeX bibliography style files.  You can use
them by placing them into a `texmf` tree in the `bibtex/bst`
directory (recommended) or in the same directory as your document.

If you're running
[the TeX Live TeX system](https://www.tug.org/texlive/) on a
Unix-like system (e.g., Linux, Mac OS X), you can create the
directories `texmf/bibtex/bst` in your home directory and copy the
`.bst` files to that directory.

On Windows, you should create `%USERPROFILE%\texmf\bibtex\bst` and
install the files in that directory.

You can also install them with MikTeX on Windows, but [it's a bit
more complicated](http://docs.miktex.org/manual/localadditions.html).


Source Code
===========

The `.dbj` files are the source files for the bibliography-style
files.  They are in docstrip batch-job files that can be compiled
with LaTeX to create the `.bst` files.

These files are based on, and derived from, Patrick W. Daly's
[`custom-bib` LaTeX package](https://www.ctan.org/pkg/custom-bib?lang=en).

To use them, you must first install `custom-bib`, copy the `.dbj`
files into the directory, and then run LaTeX on the `.dbj` files
to create the `.bst` files.


License
=======

The code in this repository can be redistributed and/or modified
under the terms of the
[LaTeX Project Public License](https://latex-project.org/lppl.txt);
either version 1 of the License, or any later version.


