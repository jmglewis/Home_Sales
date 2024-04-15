# SparkSQL Home Sales Analysis: Leveraging Spark for Key Metrics and Performance Optimization

 In this challenge, you'll find all the resources and instructions you need to analyze home sales data using SparkSQL. By leveraging the power of Apache Spark, we'll dive into the dataset to extract valuable insights and metrics about home sales.

In this project, we'll cover various aspects of SparkSQL, including creating temporary views, partitioning data, caching and uncaching tables, and optimizing query performance. Through a series of guided tasks and questions, you'll apply your SparkSQL skills to address real-world scenarios in the realm of home sales analytics.

Whether you're new to SparkSQL or looking to sharpen your skills, this project offers an opportunity to deepen your understanding of big data analytics and SQL-based data processing with Spark.


## Before You Begin
Create a new repository for this project called, Home_Sales.

Clone the new repository to your computer.

Push your changes to GitHub.

## Instructions

Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

Import the necessary PySpark SQL functions for this assignment.

Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

Create a temporary table called home_sales.

## Answer the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

Cache your temporary table home_sales.

Check if your temporary table is cached.

Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Partition by the "date_built" field on the formatted parquet home sales data.

Create a temporary table for the parquet data.

Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Uncache the home_sales temporary table.

Verify that the home_sales temporary table is uncached using PySpark.

Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.


