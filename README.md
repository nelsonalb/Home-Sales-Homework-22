# home_sales
Module 22 Challenge

# Home Sales Analysis

# Instructions:

# Step 1: Prepare and Load Data

Rename the provided 'Home_Sales_starter_code.ipynb' file to 'Home_Sales.ipynb'.
Import necessary PySpark SQL functions for the assignment.
Read the data from 'home_sales_revised.csv' into a Spark DataFrame.
Create a temporary table named 'home_sales' for further analysis.

# Step 2: Answer Questions using SparkSQL:

Utilize SparkSQL to answer the following questions:

a. Determine the average price of a four-bedroom house sold each year, rounded to two decimal places.

b. Calculate the average price of homes for each year they were built, having three bedrooms and three bathrooms, rounded to two decimal places.

c. Compute the average price of homes that have three bedrooms, three bathrooms, two floors, and are at least 2,000 square feet in size for each year they were built, rounded to two decimal places.

d. Find the "view" rating for homes priced at $350,000 or more. Display the runtime for this query, rounded to two decimal places.

# Step 3: Data Caching and Performance:

Cache the 'home_sales' temporary table and validate it.
Run the query from Step 2d on the cached table, recording the runtime and comparing it to the uncached runtime.

# Step 4: Data Partitioning and Parquet:

Create a partition based on the 'date_built' field and read the formatted parquet home sales data.
Create a temporary table for the parquet data.

# Step 5: Uncaching and Final Steps:

Uncache the 'home_sales' temporary table and verify its status.
Download the 'Home_Sales.ipynb' file and upload it to your "Home_Sales" GitHub repository.
Requirements:

Create a Spark DataFrame from the dataset.
Establish a temporary table 'home_sales'.
Write queries using SparkSQL to answer the provided questions.
Cache the 'home_sales' table and measure query runtimes.
Partition data by 'date_built' and read formatted parquet data.
Create and use a temporary table for parquet data.

