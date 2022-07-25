
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ussie

<!-- badges: start -->

[![R-CMD-check](https://github.com/mjoygroves/ussie/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/mjoygroves/ussie/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of ussie is to work with the European Football league data.
Currently, ussie capabilities makes a standard tibble for the data set.

## Installation

You can install the development version of ussie from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("mjoygroves/ussie")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(ussie)
## basic example code
italy <- uss_make_matches(engsoccerdata::italy, "Italy")
```
