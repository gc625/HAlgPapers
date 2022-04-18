# HAlgPapers
crowd sourced past paper solutions for Honors Algebra (MATH 10069) at the University of Edinburgh.

## Instructions
Using an editor like TexPad on Mac, type solutions in the `.tex` files for the respective year (eg: 1415.tex for the 2014-2015 exam), and view the output of `main.tex`

Section titles have been generated, but not neccesarily for subquestions (eg: Q1a), so please add those as you go along.

### example answer
For answers with multiple lines of equations, I prefer to use the `align` environment using `\shortintertext` (or `\st`) to place text in between equations. Use `&\` to set point of alignment for each line.

![alt text](/docs/example.png)




## Folder Structure

```bash
.
├── docs 
├── README.md
├── main.pdf
├── main.tex  
├── exam_papers 
│   ├── 1415.pdf
│   ├── 1516.pdf
│   ├── 1617.pdf
│   ├── 1718.pdf
│   ├── 1819.pdf
│   ├── 1920.pdf
│   └── 2021.pdf
├── preamble.tex
└── years
    ├── 1415.tex
    ├── 1516.tex
    ├── 1617.tex
    ├── 1718.tex
    ├── 1819.tex
    ├── 1920.tex
    └── 2021.tex
```

`exam_papers` contains PDFs of exam papers by year, 1415 = 2014-2015.

`years`  contains the tex files for you to type up solutions. 

`main.tex` is the tex files that aggregates all solutions in one 


