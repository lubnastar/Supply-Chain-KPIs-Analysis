# Supply-Chain-KPIs-Analysis

## Project Goal
This project aims to measure supplier and warehouse performance by calculating a set of key performance indicators (KPIs) commonly used in supply chain management. The analysis helps in understanding and optimizing the supply chain operations.

## Key Performance Indicators (KPIs)
The following KPIs are calculated in this analysis:

1.  **OTIF % (Perfect Order Rate)**: Percentage of orders delivered on time (or earlier) and in full quantity without shortage.
2.  **On-Time Delivery %**: Percentage of orders delivered on time (or earlier), regardless of quantity completeness.
3.  **Defective Rate %**: Percentage of damaged/defective units out of total units received.
4.  **Lead Time Variance**: Average difference between actual and promised lead time days (in days).
5.  **Total Cost Analysis**: Total expenditure aggregated by supplier and by warehouse.

## Analysis Steps
The notebook proceeds with the following steps:

1.  **Load Data**: Reads the supply chain data from `supply_chain_data.csv` into a pandas DataFrame.
2.  **Inspect and Clean**: Checks for missing values, ensures date columns are in `datetime` format, and provides a statistical summary of numerical columns.
3.  **Calculate KPIs**: Computes all the defined KPIs (OTIF %, On-Time Delivery %, Defective Rate %, Lead Time Variance, and Total Cost Analysis).
4.  **Data Visualization**: Generates various plots to visually present the calculated KPIs, including overall performance, defective rates by supplier, lead time variance by supplier, and total expenditure by supplier and warehouse.
5.  **Conclusion and Key Findings**: Provides a numerical summary of all indicators and highlights key insights for supply chain decision-makers.
