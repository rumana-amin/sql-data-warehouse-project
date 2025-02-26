# sql-data-warehouse-project
Welcome to the Data Warehouse and Analytics Project repository! 🚀  <br>
This guided project demonstrates a data warehousing and analytics solution, from building a data warehouse to generating actionable insights. 
# Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
![Data Warehouse Architecture](Docs/1_Data_Architecture.png)

**1.Bronze Layer:** Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database. <br>
**2.Silver Layer:** This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis. <br>
**3.Gold Layer:** Houses business-ready data modeled into a star schema required for reporting and analytics.

# Project Overview
This project involves:

**Data Architecture:** Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.  <br>
**ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.  <br>
**Data Modeling:** Developing fact and dimension tables optimized for analytical queries.  <br>
**Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights. <br>
