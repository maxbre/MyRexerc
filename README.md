
<!-- README.md is generated from README.Rmd. Please edit that file -->

# myRexerc

<!-- badges: start -->
<!-- badges: end -->

A package with some R programming exercises compiled with ‘learner’.

## Installing the package

You can install the development version of ‘myRexerc’ from the
repository at [GitHub](https://github.com/maxbre/myRexerc/) with:

``` r
if(!require("devtools")) install.packages("devtools")
devtools::install_github("maxbre/myRexerc")
```

## Running the exercises

You need to install the package ‘learnr’ before running the exercises
within the pakage ‘myRexerc’:

``` r
if(!require("learnr")) install.packages("leranr")
learnr::run_tutorial("test_me", package = "myRexerc")
```
