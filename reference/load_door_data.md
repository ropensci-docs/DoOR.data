# load_door_data

load all DoOR.data

## Usage

``` r
load_door_data(nointeraction = FALSE)
```

## Arguments

- nointeraction:

  if set to TRUE does not promt security message. Necessary e.g. for
  building vignettes during CHECK.

## Value

attaches all DoOR data to the main workspace

## Author

Daniel Münch \<<daniel.muench@uni-konstanz.de>\>

## Examples

``` r
# load all data to current workspace
if (FALSE) { # \dontrun{
load_door_data()
} # }

# it is also possible to load individual data sets using data().
data(Or22a)
```
