
<!-- README.md is generated from README.Rmd. Please edit that file -->

# fgitR

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
<!-- badges: end -->

[FastGit](https://doc.fastgit.org/) can work as a mirror of GitHub to
make significant acceleration.

`fgitR` is a package to do git operation with FastGit automatically.

For current stage, `fgitR` is only tested under macOS, and it should
works well on OS with POSIX. For Windows, we will test and fix in the
future.

## Installation

Once the initial development finish, we will post `fgitR` to CRAN. So
for, please install development version of `fgitR` from GitHub:
<!-- You can install the released version of fgitR from [CRAN](https://CRAN.R-project.org) with: -->

``` r
remotes::install_github("womeimingzi11/fgitR")
```

And Yes, in the future, there will be a function like
`fgitR::install_fgit("womeimingzi11/fgitR")` to accelerate the
installation of development version of `fgitR`.

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(fgitR)
## basic example code
```

<!-- What is special about using `README.Rmd` instead of just `README.md`? You can include R chunks like so: -->
<!-- ```{r cars} -->
<!-- summary(cars) -->
<!-- ``` -->
<!-- You'll still need to render `README.Rmd` regularly, to keep `README.md` up-to-date. `devtools::build_readme()` is handy for this. You could also use GitHub Actions to re-render `README.Rmd` every time you push. An example workflow can be found here: <https://github.com/r-lib/actions/tree/master/examples>. -->
<!-- You can also embed plots, for example: -->
<!-- ```{r pressure, echo = FALSE} -->
<!-- plot(pressure) -->
<!-- ``` -->
<!-- In that case, don't forget to commit and push the resulting figure files, so they display on GitHub and CRAN. -->