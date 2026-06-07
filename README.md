# Enterprise Data Quality Framework using SQL & PySpark (Banking KYC)

## SQL + PySpark + Databricks

This repo is a practical implementation of **10 Essential Data Quality Checks** using both **SQL** and **PySpark** in **Databricks**. It demonstrates how data engineers can proactively identify and prevent data quality issues before they impact analytics, reporting, machine learning models, or business decisions.

## Overview

Data quality is one of the most critical aspects of any **Analytics, Reporting, Data Engineering, or AI/ML project**. Before building dashboards, training models, or sharing insights, organizations must ensure that their data is accurate, complete, consistent, and reliable.

This repository provides a hands-on framework for validating data quality using industry-standard checks implemented in both SQL and PySpark. Integrate these checks into ETL/ELT pipelines using Airflow, dbt, Databricks, Snowflake, Azure Data Factory, or your preferred orchestration tool.

### What You'll Learn

* Detect missing and incomplete data
* Identify duplicate records
* Validate referential integrity between datasets
* Enforce business rules and accepted values
* Detect outliers and invalid ranges
* Verify data freshness
* Validate temporal consistency
* Monitor data quality degradation over time

## Data Quality Checks Covered

| #  | Check                 | Description                                 |
| -- | --------------------- | ------------------------------------------- |
| 1  | Null Checks           | Missing Mobile, Email |
| 2  | Uniqueness Checks     | Detect Duplicate Customer ID                 |
| 3  | Referential Integrity | KYC Customer Not Found      |
| 4  | Accepted Values       | Invalid Customer Status       |
| 5  | Functional Rules      | VERIFIED KYC must have expiry date          |
| 6  | Range Checks          | Negative Balance |
| 7  | Data Type Validation  | Invalid PAN Format  |
| 8  | Freshness Checks      | Old KYC Verification                   |
| 9  | Temporal Consistency  | Expiry Before Start Date       |
| 10 | Null Spike Detection  | 30%+ customers missing email   |

## Technologies Used

* Databricks
* Apache Spark
* PySpark
* SQL
* Delta Lake
* Azure Data Factory (Production Integration)
* GitHub

## Why Data Quality Matters

Poor data quality can result in:

* Incorrect business decisions
* Revenue leakage
* Broken dashboards and reports
* Failed machine learning models
* Compliance and regulatory risks
* Loss of trust in data platforms

Implementing automated data quality checks as part of your ETL/ELT pipelines helps ensure data reliability and improves confidence in downstream analytics.

## Notebook Highlights

Each data quality check includes:

✅ Business Requirement

✅ SQL Implementation

✅ PySpark Implementation

✅ Expected Output

✅ Best Practices

✅ Production Considerations

## Sample Notebook Flow

1. Create Sample Datasets
2. Execute SQL Data Quality Checks
3. Execute PySpark Data Quality Checks
4. Generate Data Quality Scorecard
5. Review Failed Records
6. Apply Production Best Practices

### Run in Databricks
Clone this repository into your Databricks Workspace using Git integration or import the notebook manually.
Attach the notebook to a Databricks cluster running Apache Spark and execute all cells sequentially to create sample datasets and run the SQL and PySpark data quality validations.

git clone https://github.com/sumitsaxena-git/enterprise-data-quality-framework.git

## Future Enhancements

* Data Quality Score Calculation
* Automated Alerting
* Data Quality Dashboard
* Great Expectations Integration
* Delta Live Tables Integration
* Azure Data Factory Pipeline Integration
* CI/CD Validation Framework

## Connect With Me

**Sumit Saxena**

Technology Lead | Data Engineering | Databricks | Azure | PySpark | AI/ML

LinkedIn: https://www.linkedin.com/in/sumitsaxenaa

GitHub: https://github.com/sumitsaxena-git

---

⭐ If you find this repository useful, please consider starring it and sharing it with the data engineering community.


