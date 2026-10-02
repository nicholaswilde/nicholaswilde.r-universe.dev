# nicholaswilde.r-universe.dev

Personal [R-universe](https://r-universe.dev) package repository registry for [@nicholaswilde](https://github.com/nicholaswilde).

## Packages

| Package | Source Repository | Description | R-universe Status |
| :--- | :--- | :--- | :--- |
| [`theamazingrace`](https://github.com/nicholaswilde/the-amazing-race) | [`nicholaswilde/the-amazing-race`](https://github.com/nicholaswilde/the-amazing-race) (`r/` subdir) | Comprehensive tidy datasets and companion R package for The Amazing Race | [![R-universe](https://nicholaswilde.r-universe.dev/badges/theamazingrace)](https://nicholaswilde.r-universe.dev/theamazingrace) |

## Installation

To install packages from this universe:

```r
# Enable this universe
options(repos = c(
  nicholaswilde = "https://nicholaswilde.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))

# Install theamazingrace package
install.packages("theamazingrace")
```

Or install directly:

```r
install.packages("theamazingrace", repos = "https://nicholaswilde.r-universe.dev")
```
