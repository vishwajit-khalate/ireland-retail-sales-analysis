# Ireland Retail Sales Performance Analysis using SQL and Excel

## Project Overview

This project analyses Irish retail sales performance using official retail sales index data. The objective is to understand how overall retail sales changed over time, compare value and volume trends, identify top-performing retail sectors, and highlight differences between sales value growth and actual sales volume growth.

## Tools Used

* Python
* Pandas
* SQLite
* SQL
* Microsoft Excel
* Pivot Charts / Dashboarding

## Dataset

The dataset used in this project is the Retail Sales Index dataset from Irish public data sources. It contains retail sales index values by year, retail sector, and statistic type.

## Key Analysis Performed

* Cleaned and prepared raw retail sales data
* Removed records with missing index values after analysing the missing-value pattern
* Loaded cleaned data into a SQLite database
* Used SQL queries to analyse:

  * Overall retail sales trend
  * Value index versus volume index
  * Top-performing retail sectors
  * Bottom-performing retail sectors
  * Sector growth from 2021 to the latest year
  * Value growth versus volume growth gap
* Exported SQL results into Excel
* Built an Excel dashboard with KPI cards, charts, and key insights


## Dashboard Preview

![Dashboard Screenshot 1](images/Screenshot1.png)

![Dashboard Screenshot 2](images/Screenshot2.png)

![Dashboard Screenshot 3](images/Screenshot3.png)

## Key Insights

1. Overall Irish retail sales value and volume increased above the 2021 base year.
2. The value index is higher than the volume index, showing that sales value grew faster than actual sales volume.
3. Bars recorded the highest value index among the top individual retail sectors.
4. The gap between value growth and volume growth may suggest price effects or changes in consumer behaviour.

## Skills Demonstrated

* Data cleaning
* Missing-value analysis
* SQL aggregation
* SQL filtering
* CASE statements
* Common Table Expressions
* Growth analysis
* Excel dashboard creation
* Business insight generation

## Project Files

* `Datasets/retail_sales_raw.csv.csv` — raw dataset
* `Datasets/retail_sales_cleaned.csv` — cleaned dataset
* `Notebooks/01_retail_sales_analysis.ipynb` — Python and SQL analysis notebook
* `dashboards/retail_sales_analysis_results.xlsx` — final Excel dashboard
* `images/retail_sales_dashboard_screenshot.png` — dashboard screenshot

## Conclusion

This project shows how SQL and Excel can be used together to clean public retail data, analyse business trends, and create a clear dashboard for decision-making.
