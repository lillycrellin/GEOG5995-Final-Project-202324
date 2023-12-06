# GEOG5995-Final-Project-202324

## GEOG5995M Final Assignment: Is Crime Occuring in More Deprived Areas of Manchester?

Lilly Crellin

This repo contains all the code used for the analysis: GEOG5995M Final Assignment: Is Crime Occuring in More Deprived Areas of Manchester?

## Background / Context of the Project:
The analysis utilises open data sources, including police-recorded crime statistics and the Index for Multiple Deprivation. The goal is to provide policymakers with valuable insights into the complex relationship between crime and deprivation by spatially and non-spatially visualising whether crime is occuring in more deprived areas of Manchester. 

## Data
Contained within the repo are Python code and associated files pertaining to the analysis. 

The primary datasets used include police-recorded crime statistics spanning from July 2018 to June 2019 and the Index for Multiple Deprivation for the same period. Additionally, a shapefile of Manchester LSOAs, subsetted from an England LSOA shapefile, is imported for spatial visualisation purposes from the UK Data Service. 

The police-recorded crime statistcs can be found [HERE](https://data.police.uk/data/statistical-data/)

The Index of Multiple Deprivation data can be found [HERE](https://data.cdrc.ac.uk/dataset/index-multiple-deprivation-imd)

The download for the relevant shapefile data can be found [HERE](https://borders.ukdataservice.ac.uk/bds.html)

## Aims
Overall the code aims to offer a comprehensive analysis of the relationship between crime and deprivation in Manchester, providing visualizations and insights that can inform policy decisions aimed at reducing crime and addressing social inequalities.

- The code employs data cleaning techniques to handle missing data and simplify the police-recorded crime dataset.
- Visualisation methods are used to understand the nature and distribution of crime. Spatial mapping techniques, including choropleth maps, illustrate the spatial distribution of crime across Manchester.
- The code introduces deprivation data and uses a generalised linear regression model to explore the correlation between deprivation and crime.

> [!NOTE]
> When using the shapefile data the specifc file used is: **england_lsoa_2011.shp** 

















