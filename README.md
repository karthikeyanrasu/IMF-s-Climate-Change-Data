# IMF's Climate Change Data

## Project Overview

This project analyzes long-term global climate trends using climate datasets from the International Monetary Fund (IMF) Climate Change Data initiative.

The analysis examines relationships among surface temperature, CO₂ concentration, sea level, and disaster frequency across countries and over time. Python-based data cleaning, statistical analysis, regression, spatial analysis, and visualization techniques were used to identify and communicate climate patterns.

## Objectives

- Analyze long-term global climate trends.
- Examine relationships between CO₂ concentration and surface temperature.
- Analyze the relationship between surface temperature and sea level.
- Examine the relationship between sea level and disaster frequency.
- Compare climate patterns across countries and regions.
- Apply statistical and spatial analysis techniques to climate data.
- Communicate analytical findings through visualizations.

## Dataset

The project uses four global climate datasets covering:

- Surface Temperature
- CO₂ Concentration
- Sea Level
- Disaster Frequency

The datasets span more than **30 years** and cover **236 countries**.

After data cleaning and preprocessing, the analysis produced **7,316 cleaned data points**.

## Data Preparation

The data preparation process included:

- Loading and inspecting the climate datasets.
- Reshaping wide-format data into analysis-ready structures.
- Handling missing values through country-level imputation.
- Creating derived features and analytical bins.
- Cleaning and validating data before statistical analysis.
- Combining relevant climate indicators for comparative analysis.

## Statistical Analysis

The project applied several statistical techniques to investigate relationships among climate variables.

### Pearson Correlation

Pearson correlation was used to measure relationships between:

- CO₂ concentration and surface temperature
- Surface temperature and sea level
- Sea level and disaster frequency

### Polynomial Regression

Polynomial regression was used to model relationships between climate variables.

Regression models with polynomial degrees from **1 through 5** were evaluated using cross-validation to identify the best-fitting relationship for each analysis.

## Spatial Analysis

GeoPandas was used to perform spatial analysis and visualize geographic differences in climate patterns.

The analysis examined climate changes across countries and identified geographic patterns in temperature changes.

Countries located near the **Arctic Circle** showed the highest temperature increases relative to the **1951–1980 baseline** in the analysis.

## Key Findings

- A **0.90 correlation** was identified between CO₂ concentration and surface temperature.
- A **0.87 correlation** was identified between surface temperature and sea level.
- A **0.50 correlation** was identified between sea-level changes and disaster frequency.
- Arctic Circle countries showed the highest temperature increases relative to the 1951–1980 baseline.

## Visualizations

The project uses multiple visualization techniques to communicate climate patterns, including:

- Boxplots
- KDE plots
- Scatter plots
- Regression visualizations
- Choropleth maps
- Multivariate visualizations

These visualizations were used to communicate long-term climate patterns and relationships among climate variables.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GeoPandas
- Scikit-learn
- Statistical Analysis
- Polynomial Regression
- Cross-Validation
- Spatial Analysis

## Project Structure

```text
IMF-s-Climate-Change-Data/
│
├── README.md
│
├── data/
│   └── climate datasets
│
├── notebooks/
│   └── climate_analysis.ipynb
│
├── visualizations/
│   └── analysis visualizations
│
└── documentation/
    └── project documentation
