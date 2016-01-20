# get_bibtex

Note: I wrote this before I realized that InspireHEP provides a (probably) better utility [here](https://inspirehep.net/info/hep/tools/bibliography_generate?ln=en).

A short script to fetch BibTeX info from InspireHEP from a LatexUS citeid. 
Useful if a LaTeX bibliography was created by pasting LaTeXUS code directly into a TeX file (as is common when 
writing hep-ph papers), but a full set of BibTeX entries is needed later, e.g., for thesis preparation.

This script extracts citeid, searches Inspire, and (if the entry was found) downloads the BibTeX entry. 
Example input and output files are provided.
