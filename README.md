# stargazer-booktabs

This is a slightly modified version of the excellent [stargazer](https://cran.r-project.org/web/packages/stargazer/vignettes/stargazer.pdf) package by Marek Hlavac.

In contrast to the main package, this fork outputs tables which use the booktabs commands `\toprule` `\midrule` and `\bottomrule` for horizontal rules. 


To install:

```R
install.packages("devtools")
library(devtools)

install_github("markwestcott34/stargazer-booktabs")
```

Make sure you include `\usepackage{booktabs}` in your LaTeX preamble.

See [the vignette](https://github.com/markwestcott34/stargazer-booktabs/blob/master/vignettes/stargazer-booktabs.pdf) for example output.
