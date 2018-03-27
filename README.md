# R-ladies_RMarkdown

This repository contains all the files used to create a presentation on using RMarkdown for doing reproducible research. The presentation was given at the R-ladies Dublin meetup on 27/03/2018. This presentation is based on a presentation previously given by myself and [Frank Loesche](https://www.cognovo.eu/people/research-fellows/frank-loesche.php), on 08/02/2017, at a *Coding Lunch* session in the [School of Psychology](https://www.plymouth.ac.uk/schools/psychology/) of Plymouth University. 

## To try RMarkdown

As of RStudio v0.98.932, RStudio comes with all the necessary packages to run RMarkdown. If you have a previous version or don't use RStudio, you will need to install pandoc and RMarkdown separately as described [here](https://github.com/rstudio/rmarkdown#installation). Also, check that you have the knitr package installed in your version of R. If not, run 'install.packages("knitr")'. If you intend to output your RMarkdown file to .pdf, you will need to have MikTeX installed as well (since RMarkdown will call the LaTeX engine to convert to .pdf). See a detailed guide on how to install MikTeX [here](https://medium.com/@sorenlind/create-pdf-reports-using-r-r-markdown-latex-and-knitr-on-windows-10-952b0c48bfa9).

## What's in this repository

The slides of the presentation in .rmd and .pdf formats are called "R-ladies-rmarkdown". Within the slides there are references to other files contained in this repository: there is an example bibliography in .bib format ("MyBibliography.bib"), a file with some basic Markdown syntax in .md, .pdf and .docx ("BasicMdSyntax"), a file with some basic RMarkdown syntax in .rmd, .pdf and .docx ("BasicRMD"). Finally, there are a few example images used in the presentation to show how different citation styles look like.

## Useful documentation

### Software + Downloads

- [knitr](https://yihui.name/knitr/)
- [Jabref](http://www.jabref.org/)
- [RStudio](https://www.rstudio.com/products/rstudio/download/)

- [LaTeX environment for Windows](https://miktex.org/)
- [LaTeX environment for Mac](https://www.tug.org/mactex/)
- [LaTeX environment for *nix -- try your package manager first](https://www.tug.org/texlive/)

- [Citation Style (CSL) downloads](https://github.com/citation-style-language/styles-distribution)


### Language References

- [Markdown syntax](https://daringfireball.net/projects/markdown/syntax)
- [Pandoc manual (also Markdown syntax)](http://pandoc.org/MANUAL.html)
- [RMarkdown documentation](http://rmarkdown.rstudio.com/lesson-1.html)
- [RMarkdown reference](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf)

- [knitr options](https://yihui.name/knitr/options/)
- [book about dynamic documents (knitr and Sweave)](https://github.com/yihui/knitr-book)
- [Wikibook on publication quality output](https://en.wikibooks.org/wiki/R_Programming/Publication_quality_ouput)

- [BibTex reference](http://www.bibtex.org/Format/)
- [BibLaTeX reference](https://www.ctan.org/pkg/biblatex)

- [Citation Styles (CSL)](http://citationstyles.org/)

### Examples

- [knitr examples](https://github.com/yihui/knitr-examples)
    
### Further Readings

- [Literate Programming (original article)](https://doi.org/10.1093/comjnl/27.2.97)
- [Argument to create reproducible research](https://www.washingtonpost.com/news/speaking-of-science/wp/2015/08/28/no-sciences-reproducibility-problem-is-not-limited-to-psychology/)
- [Replication Crisis](https://en.wikipedia.org/wiki/Replication_crisis)
-[Example of Swiss data journalism](http://srfdata.github.io/)
- [Other approach to writing Articles (rticles)](https://github.com/rstudio/rticles)

### Useful packages

- [Table method 1, looks interesting](https://github.com/renkun-ken/formattable)
- [Table method 2, with a few predefined format options](http://rpubs.com/jalapic/simpletable2)
- [Pander, interesting tool for converting R objects into rmarkdown](http://rapporter.github.io/pander/)
- [sjplot, nice collection of functions to visualise various R outputs, including regression tables](https://github.com/strengejacke/sjPlot)
- [stargazer, to create tables in tex or html format to export to other documents](https://www.r-bloggers.com/stargazer-package-for-beautiful-latex-tables-from-r-statistical-models-output/)

