# MySQL Layoffs Data Analysis Project

## Project Overview

This project focuses on analyzing layoff data from **2020 to 2023** using **MySQL**. The dataset contains information about company layoffs across different industries, countries, funding stages, and time periods.

The project is divided into two main parts:

1. **Data Cleaning** – Handling null values, removing duplicates, standardizing data, and preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA)** – Performing SQL queries to identify trends, patterns, and insights from the layoffs dataset.

---

## Dataset Used

The dataset includes details such as:

* Company Name
* Industry
* Total Laid Off
* Percentage Laid Off
* Date
* Stage
* Country
* Funds Raised

Time Period Covered:
**2020 – 2023**

---

## Tools & Technologies

* **MySQL**
* SQL Queries
* MySQL Workbench
* Git & GitHub

---

## Project Steps

### 1. Data Cleaning

Performed the following cleaning operations:

* Removed duplicate records
* Standardized company names
* Fixed inconsistent industry values
* Converted date formats properly
* Handled null and missing values
* Removed unnecessary columns if required
* Checked and corrected blank spaces and formatting issues

This ensured the dataset was accurate and ready for analysis.

---

### 2. Exploratory Data Analysis (EDA)

Performed analysis to answer questions like:

* Which companies had the highest layoffs?
* Which industries were most affected?
* Which countries had the most layoffs?
* Layoff trends by year and month
* Companies with 100% layoffs
* Funding stage vs layoffs analysis
* Top companies by total layoffs
* Year-wise layoff comparison

---

## Sample SQL Concepts Used

* `ROW_NUMBER()`
* `CTE (Common Table Expressions)`
* `GROUP BY`
* `ORDER BY`
* `PARTITION BY`
* `JOIN`
* `CASE WHEN`
* Aggregate Functions (`SUM`, `AVG`, `MAX`, `MIN`)
* Date Functions

---

## Key Insights

Some important findings from the analysis:

* Tech companies experienced major layoffs during 2022–2023
* Several startups had 100% workforce layoffs
* United States showed the highest number of layoffs
* Late-stage funded companies also faced significant layoffs
* Layoff peaks were clearly visible during economic slowdown periods

---

## Learning Outcome

Through this project, I improved my understanding of:

* Real-world SQL data cleaning
* Writing optimized SQL queries
* Business problem solving using SQL
* Exploratory Data Analysis using MySQL
* Data-driven decision making

---

## Repository Structure

```text
MYSQL-Layoffs-Project/
│
├── layoffs.csv
├── data_cleaning.sql
├── exploratory_data_analysis.sql
└── README.md
```

---

## Future Improvements

* Create Power BI dashboard for visualization
* Build Tableau reports
* Perform advanced trend forecasting
* Add Python-based analysis

