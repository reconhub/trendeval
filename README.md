
<!-- README.md is generated from README.Rmd. Please edit that file -->

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/trendeval)](https://CRAN.R-project.org/package=trendeval)
[![Codecov test
coverage](https://codecov.io/gh/reconhub/trendeval/branch/master/graph/badge.svg)](https://codecov.io/gh/reconhub/trendeval?branch=master)
[![R build
status](https://github.com/reconhub/trendeval/workflows/R-CMD-check/badge.svg)](https://github.com/reconhub/trendeval/actions)
<!-- badges: end -->

<br> **<span style="color: red;">Disclaimer</span>**

This package is a work in progress. Please reach out to the authors
before using.

# Trendeval

*trendeval* aims to provide a coherent interface for evaluating models
fit with the [trending](https://github.com/reconhub/trending) package.
Whilst it is useful in an interactive context, it’s main focus is to
provide an intuitive interface on which other packages can be developed
(e.g. [*trendbreaker*](https://github.com/reconhub/trendbreaker)).

## Installing the package

Once it is released on [CRAN](https://CRAN.R-project.org), you will be
able to install the stable version of the package with:

``` r
install.packages("trendeval")
```

The development version can be installed from
[GitHub](https://github.com/) with:

``` r
if (!require(remotes)) {
  install.packages("remotes")
}
remotes::install_github("reconhub/trendeval", build_vignettes = TRUE)
```

# Resources

## Getting help online

Bug reports and feature requests should be posted on *github* using the
[*issue* system](https://github.com/reconhub/incidence2/issues). All
other questions should be posted on the **RECON** slack channel see
<https://www.repidemicsconsortium.org/forum/> for details on how to
join.
