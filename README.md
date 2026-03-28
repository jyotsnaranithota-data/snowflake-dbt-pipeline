# Automated ELT Pipeline using Snowflake, dbt, and AWS

## 📌 Overview

This project demonstrates an end-to-end ELT pipeline built using Snowflake, dbt, and AWS S3. The pipeline ingests raw sales data (CSV files), transforms it, and produces analytics-ready datasets for business reporting.

## 🚀 Architecture

Data Source (CSV) → AWS S3 → Snowpipe → Snowflake (Raw Tables) → dbt Transformations → Analytics Tables

## 🛠️ Tech Stack

* Snowflake (Data Warehouse)
* dbt (Data Transformation Tool)
* AWS S3 (Storage Layer)
* SQL

## ⚙️ Implementation Steps

1. Created sample sales datasets (customers, orders)
2. Uploaded data to AWS S3 bucket
3. Created Snowflake stage to connect with S3
4. Used Snowpipe for automated data ingestion
5. Loaded data into raw tables in Snowflake
6. Built dbt models (staging and marts) for transformation
7. Created final analytics table with aggregated sales metrics
8. Applied dbt tests for data validation

## 📊 Key Features

* Automated data ingestion using Snowpipe
* Incremental data processing using dbt
* Data quality checks using dbt tests
* Scalable ELT pipeline design

## 📈 Output

Final output table contains:

* Customer ID
* Customer Name
* Total Sales per Customer

## 📸 Screenshots

(Will Add more screenshots of Snowflake tables, query results, dbt run output if required)

## 💡 Learning Outcome

* Gained hands-on experience with ELT pipeline design
* Learned Snowflake data loading and staging concepts
* Implemented dbt transformations and testing
* Understood real-world data engineering workflow

## 👩‍💻 Author

Jyotsna Rani Thota
