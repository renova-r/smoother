# smoother

Functions for smoothing numerical data: a port of the Matlab Gaussian window smoother and several moving averages from the TTR package.

Compatibility updates by Renova.

Version 1.3.9001 makes metadata and documentation changes and no R code change. The stale optional `Date` field was removed, the author is also listed in an `Authors@R` entry (`Author` reads `Nicholas Hamilton [aut, cre]`; maintainer address unchanged), and the `\link` to TTR in `man/smoother.Rd` is now `\link[TTR]{TTR}`.

## Install

From R-universe:

```r
install.packages("smoother", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or the exact release tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/smoother@renova-1.3.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

smoother was written by Nicholas Hamilton (maintainer). License: GPL-2 (see [COPYING](COPYING)).
