# Crowdfunding ETL Project

This repository contains the source code and data files for the Crowdfunding ETL (Extract, Transform, Load) project. The project involves extracting data from Excel files, transforming it using Python and Pandas, and loading it into a PostgreSQL database.

## Project Overview

In this project, we performed the following tasks:

1. **Extracted data**: We extracted data from Excel files (`crowdfunding.xlsx` and `contacts.xlsx`) containing information about crowdfunding campaigns and contacts associated with those campaigns.

2. **Transformed data**: We used Python and Pandas to transform the extracted data. This included creating separate DataFrames for categories, subcategories, campaigns, and contacts, as well as converting data types, splitting columns, and cleaning the data.

3. **Created a database schema**: Based on the transformed data, we designed a relational database schema using PostgreSQL. This schema includes tables for campaigns, categories, subcategories, and contacts, with appropriate primary keys and foreign key constraints to maintain data integrity.

4. **Loaded data into PostgreSQL**: We created a new PostgreSQL database named `crowdfunding_db` and executed SQL commands to create tables according to the schema and import data from CSV files into the respective tables.

## Repository Structure

- `ETL_Mini_Project_KJain_SKumari.ipynb`: Jupyter Notebook containing the Python code for extracting, transforming, and loading the data.
- `Resources/`: Directory containing the Excel files (`crowdfunding.xlsx` and `contacts.xlsx`) used in the project.
- `crowdfunding_db_schema.sql`: SQL file containing the database schema for creating tables in PostgreSQL.
- `category.csv`, `subcategory.csv`, `campaign.csv`, `contacts.csv`: CSV files containing the transformed data for each table.

## Instructions for Use

1. Clone this repository to your local machine.
2. Ensure you have Python and PostgreSQL installed.
3. Open and run the `ETL_Mini_Project.ipynb` notebook to perform the ETL process.
4. Execute the SQL commands in `crowdfunding_db_schema.sql` to create the database schema in PostgreSQL.
5. Import the CSV files into the `crowdfunding_db` database using PostgreSQL's `COPY` command.
6. Verify that the data has been successfully loaded into the database by running SELECT queries.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- PostgreSQL

## Contributors

- [Kashish Jain](https://github.com/kasheshjaiin)
- [Partner's Name](https://github.com/partnerusername)
