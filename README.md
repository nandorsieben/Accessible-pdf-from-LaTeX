# Accessible pdf from LaTeX

This is an attempt to create a pdf using LaTeX with a high accessibility score.

The latex document compiles with 
```
lualatex sample.tex
```
It requires a recent version (Version 1.22.0) of lualatex (https://www.tug.org/texlive/) that is likely not available in standard Linux packages. Manual installation is probably required using the install-tl script. This version of lualatex is available on overleaf.

The created pdf has an accessibility score of 100% on canvas.

I was not able to include other environments (proof, proposition). Please provide pull requests if you know how to add more features.
