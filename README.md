# Exploratory data analysis

## Goals:

- Understand the data’s structure, quality, and key statistics
- Identify patterns, trends, and outliers
- Merge your findings with demographic and geographic context (demografia_gestosc.xlsx, demografia_str_lud.xlsx)
- Present results through interactive maps that clearly communicate your insights


## Dataset 3 - Beds per Hospital

- Distribution of hospital beds by region and specialty.
- Trends in capacity over time.
- Areas with low capacity vs. demand.

## Other datasets

- Population density data (demografia_gestosc.xlsx)
  - Use for normalizing values (e.g., beds per 1,000 people).
- Population structure data (demografia_str_lud.xlsx)
  - Use for age-specific or gender-specific analysis.


## Definition of Done:

- Data cleaning & preparation
- Handle missing values, incorrect types, and duplicates.
- General EDA
  - Summary statistics (mean, median, min, max, standard deviation)
  - Distribution plots for key metrics
  - Time series plots for trends
  - Outlier detection
- Ensure geographic identifiers (Województwo, Powiat, Gmina, TERYT) match across datasets
- Merge geographic and population data to:
  - Calculate per-capita measures.
  - urban vs. rural (differences)
  - Compare across population density levels.
  - Interactive maps
  - Base map: Poland by Województwo and Powiat with metric (heatmap)
  - Tooltips with detailed information
  - Filters for year, specialty, medical category, as well as population structure