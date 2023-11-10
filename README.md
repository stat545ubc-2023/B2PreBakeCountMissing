
<!-- README.md is generated from README.Rmd. Please edit that file -->

# B2PreBakeCountMissing

<!-- badges: start -->
<!-- badges: end -->

The goal of B2PreBakeCountMissing is to count missing values for all
columns by group in a dataframe

## Installation

You can install the development version of B2PreBakeCountMissing from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("stat545ubc-2023/B2PreBakeCountMissing")
```

## Example

This is a basic example which shows you how to solve a basic problem:

``` r
library(B2PreBakeCountMissing)
countMissing(airquality, Month)
#> # A tibble: 5 × 6
#>   Month Ozone Solar.R  Wind  Temp   Day
#>   <int> <int>   <int> <int> <int> <int>
#> 1     5     5       4     0     0     0
#> 2     6    21       0     0     0     0
#> 3     7     5       0     0     0     0
#> 4     8     5       3     0     0     0
#> 5     9     1       0     0     0     0
```
