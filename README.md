# Analyzing Runkeeper App Data

- Kevin Barnett

## Business Problem
Analyze a runner's data from the popular running app 'Runkeeper' and report insights about their training habits, style, and performance trends/achievements. The runner has specifically requested to find out if he has reached his goal of running 1000km per year, he is progressing, and what his training intensity is.

## Data Methodology
1. Gather Data
2. Data Cleaning
3. Exploratory Data Analysis
4. Detailed Statistical Summary

## Gathering Data
The runner was able to supply the data from the 'Runkeeper' app by downloading and sending the data in a .csv file format.

## Data Cleaning
After loading the data into a pandas dataframe the follow steps were completed to clean the data:
    - Columns that were not relevant to the analysis were dropped
    - 'Other' column was renamed to 'Unicycling'
    - Averages of the columns were used to fill missing data points

## Exploratory Data Analysis