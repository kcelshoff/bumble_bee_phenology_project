2025-02-05
Kyle Elshoff

This folder contains all of the cleaned, transformed, augmented, or otherwise manipulated data derived from the original raw data file sent to me by Leif Richardson in September 2024. These CSVs are produced via R scripts that can be found ordered in the "scripts" folder.

Contents of this folder include:

"avg_climate_data.csv" = contains average temperature and precipitation data for each bumble bee occurrence site in our dataset, derived from Daymet Version 4 climate data. This dataset was compiled by an R script.

"bumbles_filtered.csv" = contains the near-final bumble bee occurrence dataset used in the project--all records from the raw data were cleaned (removing duplicates, correcting erroneous information) and filtered to the scope of our study. However, this is not the final bumble bee dataset because it hasn't been joined with the climate data yet, and because there were a handful of records for which we could not retrieve climate data, the final dataset is a bit smaller.

"bumbles_final.csv" = final, curated bumble bee dataset used for all analyses.

"griseocollis_castes.csv" = final dataset of all queen and male occurrences of B griseocollis used for analyses for question 3.

"impatiens_castes.csv" = final dataset of all queen and male occurrences of B impatiens used for analyses for question 3.

"north_america_points.csv" = data used to generate maps of bumble bee occurrences and climate data

"year_climate.csv" = contains yearly temperature and precipitation data for each bumble bee occurrence site-year combination in our dataset, derived from Daymet Version 4 climate data. This dataset was compiled by an R script.



