# federal-spending-analysis
Python analysis of U.S. federal contract and grant spending using USAspending.gov data, with agency, geographic, and multi-year trend analysis.
# Federal Spending Analysis

## Overview

This project analyzes U.S. federal contract and grant spending using public data from USAspending.gov. The goal is to understand how federal award dollars are distributed across agencies, award types, states, and over time.

The analysis was completed in Python using the USAspending API, pandas, Matplotlib, and Plotly.

## Research Question

How does the federal government distribute contract and grant funding across agencies and states, and what patterns emerge in how that funding is allocated?

## Data Source

- USAspending.gov
- Federal contract and grant award data
- Fiscal years 2021–2025

## Tools Used

- Python
- pandas
- requests
- Matplotlib
- Plotly
- Jupyter Notebook

## Key Findings

- The Department of Health and Human Services and the Department of Defense account for a large share of federal contract and grant spending.
- The top two agencies accounted for about 71.8% of the spending in the agency dataset.
- Grant spending was substantially higher than contract spending in fiscal year 2025.
- Federal agencies use contracts and grants very differently depending on their missions.
- Federal award spending is geographically concentrated, with higher totals in states such as California and several states in the Northeast.
- Grant spending changed more sharply over time than contract spending, especially following the pandemic-era spending peak in 2021.

## Visualizations

This project includes:

1. Top federal agencies by contract and grant spending
2. Federal contract vs. grant spending
3. Contract vs. grant spending by agency
4. Federal contract and grant spending by state
5. Federal contract and grant spending over time

## Project Files

- `federal_spending_analysis.ipynb` — full Python analysis
- `Federal_Spending_Analysis.pdf` — final written report

## Methodology

Data was retrieved from the USAspending.gov API and analyzed in Python. pandas was used to clean, organize, and calculate the data. Matplotlib was used for bar and line charts, while Plotly was used to create the geographic spending map.

The geographic analysis uses place-of-performance data, which represents where the federally funded work or activity is recorded as taking place.

## Limitations

This project focuses on federal contracts and grants rather than all federal spending. State-level results are based on total spending, so larger states may naturally receive higher totals. The analysis identifies patterns and relationships but does not prove that any single factor caused a particular spending outcome.

## Author

Kristoffer Fields  
Master of Science in Analytics  
Georgia Institute of Technology
