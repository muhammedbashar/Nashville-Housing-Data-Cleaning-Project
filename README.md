# Nashville Housing Data Cleaning (MySQL)
### Project Overview

This project focuses on cleaning and preparing raw Nashville housing data using MySQL to make it analysis-ready. The dataset contained inconsistent date formats, missing addresses, duplicate records, and unstructured text fields. All data cleaning was performed directly in SQL, simulating a real-world database environment.

### Key Objectives

* Standardize date formats for consistency

* Populate missing property addresses using relational logic

* Split address fields into structured components

* Normalize categorical values for clarity

* Identify and remove duplicate records

* Remove unused columns to optimize the dataset

### Key Data Cleaning Steps

* Date Standardization: Converted raw sale dates into a uniform date format

* Missing Value Handling: Filled missing property addresses using Parcel ID relationships

* Data Normalization: Converted Y/N values into clear Yes/No labels

* Data Structuring: Split property and owner addresses into separate address, city, and state columns

* Duplicate Removal: Identified and removed duplicate records using window functions

* Schema Optimization: Dropped unused columns after cleaning

### Key SQL Concepts Used

  * UPDATE with JOIN

  * CASE statements

  * COALESCE and NULLIF

  * String functions (SUBSTRING_INDEX)

  * Window functions (ROW_NUMBER() OVER)

  * Common Table Expressions (CTEs)

  * Schema modifications (ALTER TABLE, DROP COLUMN)

### Outcome

The final dataset is clean, structured, and analysis-ready, demonstrating practical SQL skills commonly used in real data analyst and data engineering workflows.

### Tools Used

MySQL / MySQL Workbench
