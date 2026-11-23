# Cyclistic Bike-Share Analysis Case Study

## Project Overview
This case study analyzes historical bike-share trip data from **Cyclistic** (a bike-share program in Chicago) to understand how **annual members** and **casual riders** use the service differently. The insights and visualizations from this analysis aim to support the marketing team in designing targeted strategies to convert casual riders into profitable annual members.

## Analytical Process (6 Phases)
1. **Ask:** Defined the business task and key stakeholders (Director of Marketing Lily Moreno and the Executive Team).
2. **Prepare:** Merged and verified 12 months of historical trip data (`Cyclistic-22-23`), documenting the historical period April 2022-March 2023 and data limitations.
3. **Process:** Cleaned missing/invalid records, standardized date formats, and engineered features such as `ride_length` and `day_of_week`.
4. **Analyze:** Conducted descriptive statistics and behavioral comparisons across rider types, days of the week, and peak hours.
5. **Share:** Created visualizations highlighting key usage patterns between casual riders and annual members.
6. **Act:** Provided data-driven marketing recommendations focused on weekend passes, seasonal promotions, and commuter incentives.

## Tools Used
* **Python** (`pandas`, `numpy`, `matplotlib`, `seaborn`)
* **Jupyter Notebook / Kaggle**

## Files in This Repository
* `cyclistic-bike-share-case-study.ipynb`: Complete Jupyter Notebook containing data cleaning, analysis, visualizations, and business recommendations.

## Educational Context, Data Sources and Reuse

This is an educational portfolio case study based on the bike-share scenario in the Google Data Analytics capstone on Coursera. Cyclistic is the course scenario, not a client that commissioned this analysis. Business recommendations are proposed exercises, not implemented results.

The notebook used the Cyclistic-22-23 Kaggle compilation by mohammedmustafa648: https://www.kaggle.com/datasets/mohammedmustafa648/cyclistic-uncleaned-data . The saved notebook inputs cover April 2022 through March 2023. The compilation's current license field is Unknown; this project does not claim that the uploader granted unrestricted rights.

The underlying trip-data source is documented as Divvy system data: https://divvybikes.com/system-data . The official data terms are at https://divvybikes.com/data-license-agreement . The terms allow lawful analysis and use, but prohibit standalone dataset redistribution, re-identification of riders and implied endorsement. They also place conditions on publishing data as source material in non-commercial analyses and restrict use of trademarks. A notebook code license does not replace those data terms.

This repository contains analysis code, saved results and documentation, not a standalone raw trip-data download. For reproducibility, the recommended next step is to obtain the corresponding monthly files from the official source, rerun the analysis and record the exact file names and access date. Until then, the mirror's complete provenance is not independently established.
