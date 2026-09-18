# Flight Delay Analysis using Python

## Project Overview

This project analyzes flight data to understand patterns in flight delays, cancellations, and diversions.

The analysis focuses on airlines, airports, months, years, and different delay reasons using Python data analysis and visualization libraries.

## Objectives

- Analyze flight delay patterns across different years and months.
- Identify airlines and airports with highest delayed flights.
- Analyze major reasons responsible for delays.
- Study flight cancellations and diversions.
- Compare total flights with delayed flights.
- Analyze average arrival delays across months and airlines.
- Present findings using clear data visualizations.

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Hugging Face Datasets

## Dataset

The dataset was loaded from an online dataset repository using the Hugging Face `datasets` library.

The dataset contains information about flights, airlines, airports, delays, cancellations, diversions, and different delay reasons.

## Data Cleaning

- Original dataset: 171,666 rows
- Cleaned dataset: 171,223 rows
- No duplicate records were found.
- Missing values were removed using `dropna()`.
- The cleaned dataset contains no missing values.

## Analysis Performed

- Top 10 Airlines by Total Delayed Flights
- Top 10 Airlines by Delay Rate
- Monthly Flight Delays
- Flight Delays by Reason
- Cancelled vs Non-Cancelled Flights
- Top 10 Airports by Delayed Flights
- Top 10 Airlines by Cancelled Flights
- Year-wise Flight Delays
- Weather Delay vs Total Arrival Delay
- Flight Delay Correlation
- Distribution of Arrival Delays
- Top 10 Airlines by Average Arrival Delay
- Average Arrival Delay by Month
- Total Flights vs Delayed Flights
- Year-wise Cancelled Flights
- Year-wise Diverted Flights

## Key Insights

- August recorded the highest number of flight delays.
- 2019 had the highest yearly flight delays.
- Late aircraft delays were the major contributor to total delays.
- Southwest Airlines had the highest number of delayed flights.
- Chicago O'Hare Airport recorded the highest number of delayed flights.
- Weather delays contributed to overall arrival delays and varied across different years.
- Flight cancellations and diversions varied across different years.

## Future Scope

- Flight delay prediction can be performed using Machine Learning.
- Real-time flight data can be incorporated for live delay monitoring.
- Weather information can be combined with flight data for deeper analysis.
- An interactive dashboard can be developed using Power BI.
- Route-level analysis can be performed to identify frequently delayed routes.

## Project File

The complete analysis is available in the Jupyter Notebook:

`project.ipynb`
