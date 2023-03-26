# ACS Data Analysis

This repository contains code for analyzing data from the American Community Survey (ACS) using R packages such as GISTools, sf, sp, tmap, rgdal, tidyverse, ggplot2, gridExtra, and grid.

## Load Libraries

The following libraries are used in the code:

- GISTools
- sf
- sp
- tmap
- rgdal
- tidyverse
- ggplot2
- gridExtra
- grid

## Load Data

The code reads in the following shapefiles:

- acs.shp
- roads.shp

## Data Analysis

The following statistics are calculated for various columns in the acs data frame:

- Total population
- Percent population with a college degree
- Median household income
- Poverty rate
- Percent population without health insurance
- Percent households without a vehicle

Boxplots and scatterplots are created for the above columns, and maps are created using tmap.

## Dependencies

The code requires the following R packages:

- GISTools
- sf
- sp
- tmap
- rgdal
- tidyverse
- ggplot2
- gridExtra
- grid

You can install these packages using the following command:


## Authors

This code was written by Taylor Quade.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
