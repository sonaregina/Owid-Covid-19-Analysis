# Owid-Covid-19-Analysis

## Introduction
This project focuses on conducting Exploratory Data Analysis (EDA) on the Our World in Data COVID-19 dataset using Python. The objective is to gain meaningful insights from the data by exploring patterns, trends, and anomalies related to COVID-19 cases, deaths, and vaccinations across different countries. After the analysis, an interactive dashboard is developed using Google Looker Studio to visually present the results and facilitate better understanding for end users.

## Data Cleaning and Preparation
Several steps were taken to clean and prepare the data for analysis:
* Filtering locations by continent: Entries that do not belong to any recognized continent were removed to ensure consistency and relevance.
* Dropping columns with more than 50% missing values: These were considered unreliable for analysis.
* Replacing NaN values: For columns with less than 50% missing data, missing values were filled with 0 to prevent errors during analysis.
* Data type conversions: Dates were formatted properly, and numeric columns were standardized.
These preprocessing steps were essential to eliminate noise and maintain the integrity of the dataset.

## Exploratory Data Analysis (EDA)
For the EDA process, the project utilized the Pandas Profiling library. This tool provided an automated overview of the dataset, generating a detailed report that includes:
* Distribution of numerical features
* Correlation heatmaps
* Missing data matrix
* Descriptive statistics for each feature
* Identification of outliers and duplicate rows
The use of Pandas Profiling streamlined the EDA process, enabling fast discovery of key trends and relationships within the dataset.

## Dashboard
An interactive dashboard was developed using Google Looker Studio to visualize the insights derived from the cleaned data. The dashboard offers:
* Time-series charts for confirmed cases and deaths
* Vaccination progress across countries and continents
* Country-level comparisons for key metrics
* Custom filters to select date ranges or specific regions

👉 Access the live dashboard here: [https://lookerstudio.google.com/u/2/reporting/c1197e0f-d66d-416d-9659-fd422e0a5d62/page/f980D]

The dashboard helps users, including researchers and policy-makers, to quickly explore and understand the COVID-19 situation globally through intuitive visualizations.
