# Project Title: CSV to PostgreSQL ETL (Extract, Transform, Load) Automation

![1_7AOhGDnRL2eyJMUidCHZEA](https://github.com/rickashewilliams19/PostgreSQL-Data-Ingestion-from-CSV/assets/88403017/894b38b8-96af-4aa3-8a63-e4d94b69ed26)

Introduction:

This project is designed to automate the process of extracting data from CSV (Comma-Separated Values) files, transforming and cleaning that data, and then loading it into a PostgreSQL database. ETL is a fundamental process in data engineering and analysis, and this project streamlines these essential steps.

Project Overview:

Data Extraction: The project begins by importing two CSV files, namely Wealth-AccountsCountry.csv and Wealth-AccountSeries.csv. These files contain valuable information, but they may have missing or unnecessary data.

Data Cleaning and Transformation: The imported data is thoroughly cleaned and transformed using the Pandas library in Python. This includes removing rows with missing values, selecting specific columns of interest, and ensuring data consistency.

Data Export: After cleaning and transformation, the cleaned data from the AccountsSeries DataFrame is exported to a new CSV file named "your_output_file2.csv." This export ensures that the cleaned data is readily available for future analysis or sharing.

Database Creation: The script connects to a PostgreSQL database named "accounts." If the database does not exist, it is created. This step requires the configuration of a PostgreSQL server and valid credentials.

Table Creation: Within the "accounts" database, two tables are created: "accountscountry" and "accountsseries." These tables are designed to accommodate the specific data from the CSV files.

Data Loading: The cleaned data is inserted into these tables using SQL INSERT INTO statements. This step establishes a structured and organized database for efficient data retrieval.

Data Querying: To verify the successful data transfer and database creation, the script executes SQL queries to retrieve data from both "accountscountry" and "accountsseries" tables. The results are printed, demonstrating that the data is accessible for analysis.

Conclusion:

In summary, this project showcases an end-to-end ETL process, starting from data extraction from CSV files, through data cleaning and transformation, to the loading of cleaned data into a PostgreSQL database. It serves as a foundational step in data analysis and database management, providing a structured and organized repository for valuable data. The automation aspects of the project make it scalable and repeatable for future data updates and analyses.
