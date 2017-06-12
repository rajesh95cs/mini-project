# Rajesh_miniproject_report

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

The repository contains the necessary latex files to compile the Mini project report of the author.

### How do I get set up? ###

Latex document which can compiled from the tex file miniProject.tex

### List of files required for compilation

miniProject.tex

### Contribution guidelines ###

The author is Rajesh R Nair

### Who do I talk to? ###

The rights of the document lies solely with the author.

### How to compile 

Use pdflatex to compile the document as:

xelatex miniProject.tex && xelatex miniProject.tex

in the terminal.

To compile the file with references use the command

xelatex miniProject.tex && bibtex miniProject.aux && xelatex miniProject.tex && xelatex miniProject.tex
