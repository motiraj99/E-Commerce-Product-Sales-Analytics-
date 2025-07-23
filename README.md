# E-Commerce-Product-Sales-Analytics

1) Frameworks & tools Azure Databricks, Datalake, Spark Sql, Pyspark
2) Data Ingestion from Azure: Ingested e-commerce data (customers, orders, products) using Autoloader into Delta Lake tables.
3) Real-Time & Incremental Processing: Used Structured Streaming for real-time data updates and implemented incremental loading strategies.
4) Medallion Architecture Design: Organized data into Bronze (raw), Silver (cleaned), and Gold (analytics-ready) layers.
5) Data Governance with Unity Catalog: Managed secure access, auditing, and lineage using Unity Catalog across the pipeline.
6) ETL with Delta Live Tables: Built declarative ETL pipelines supporting SCD Type 1 & 2 for historical tracking and dimension management.
7) Star Schema for Analytics: Modeled data in a Star Schema format to support efficient reporting and product sales insights

# Description of files
1) notebooks.dbc : consists of 10 python notebooks used for the project
2) parquet files related to orders, customers, products and regions used as source data for the project.

# The End to End Pipeline looks as follows:
Medallion architecture: organized data into Bronze, Silver and Gold layers.
Data is cleaned and then processed in subsequent layers.
The final data in Gold layer is ready to be used by Data Analysts and Data Scientists.
Star Schema is used to get insights into data. (Fact_Orders Table)
<img width="1476" height="439" alt="Untitled picture_11" src="https://github.com/user-attachments/assets/92af5e10-9413-4c2a-84c2-a0f04f45464e" />

