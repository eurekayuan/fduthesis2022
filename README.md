# Fudan Thesis 2022
LaTeX thesis template for CS undergraduates, Fudan University, 2022.
The template follows the official instructions [计算机学院、软件学院本科毕业论文撰写规范.docx](计算机学院、软件学院本科毕业论文撰写规范.docx) provided by the CS department.

See [fducs2022_thesis_template.pdf](fducs2022_thesis_template.pdf) for an example of the output.

## Usage
Directly open the Overleaf template from this [link](https://www.overleaf.com/latex/templates/fducs2022-thesis-template/vhktvztpykpw), or follow the following steps:

Download the zip version of this repo. Open a new project on [Overleaf](https://www.overleaf.com/project) and upload the zip file. Compile `main.tex` and it's done. Remember to switch the compiler to `XeLaTeX`, or you will encounter problems.

## Miscellaneous
If you encounter overflow of table of contents, you may solve the problem by adding the following line before the source code of the first section that overflows.
```tex
\addtocontents{toc}{\protect\newpage\protect}

% \section{xxx}
% xxx is the first section that overflows in ToC
```
