# coverletter-and-cv

Project creates a resume and a cover letter using the altacv package. Output is stored in build folder.
Enter companies and personal information in file personalInformation.tex. Content for the cover letter and 
resume is located in the folders with the extension Content.

Tested on pdflatex (pdfTeX, Version 3.141592653-2.6-1.40.22 (MiKTeX 21.3)) and latexmk (Version 4.72b):
```
latexmk -pdf -synctex=1 -interaction=nonstopmode -file-line-error -output-directory=build application.tex
```
