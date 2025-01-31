# Forecasting Winter Bed Occupancy
Author: marcos fabietti (email: marcos.fabietti@nhs.net)
Date: 31/01/2023

## Overview

This project forecasts hospital bed occupancy during the winter period, focusing on elective and emergency admissions. The analysis is based on historical data from Nottingham University Hospitals and includes forecasting models to predict patient flow. Read the article about it here: [Data-Driven Insights: Forecasting and Acting on Hospital Occupancy for the Post-Christmas Surges in an NHS Trust | by Marcos Fabietti | Jan, 2025 | Medium](https://medium.com/@mifabietti/data-driven-insights-forecasting-and-acting-on-hospital-occupancy-for-the-post-christmas-surges-in-0cc10e6281b7)

## Features

-   **Elective Analysis**: Forecasting bed occupancy for planned admissions.
-   **Emergency Analysis**: Predicting occupancy for unplanned admissions.
-   **Aggregate Forecasts**: Combining elective and emergency occupancy models.
-   **Posterior Validation**: Evaluating model accuracy using validation data.

## Requirements

To run the notebook, install the necessary dependencies:

```bash
pip install pandas numpy matplotlib prophet darts 

```

## Usage

1.  Load the synthetic dataset into the notebook.
2.  Run the preprocessing and forecasting cells.
3.  Evaluate the results with posterior validation.

## Results

The forecasts help NHS hospitals plan capacity and resource allocation during high-demand winter periods.


## Data
  
The dataset is organised in two  CSV files. Their structure includes:
| Date       | Elective	 | Emergency | 
| ---------- | ---------------------- | ---------------------- | ------------------------------------ | --------------------- |
| 01/04/2021 | 90                 | 475                     | 

-   **Date:** Date of record.
    
-   **Elective	:**  Elective  patients occupancy per day.
    
-   **Emergency  :** Emergency  patients occupancy per day.