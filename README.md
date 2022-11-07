# Northwinds-Table
Repository for Analysis of Northwinds Dataset

## Using SQL queries to do a complex analysis of Northwinds tables.
## Prerequisites:
-Install Microsoft SQL Server 2019. If you already have SQL Sever 2012-2017 installed, the code should run just fine.

-Install SQL Server Management Studion (SSMS).

-Execute NorthwindsDB_Setup file.

## Questions:
1. What are our highest value customers?
2. What are the orders made at the end of the month?
3. Which orders are late?
4. Which salespeople have the most orders arriving late?
5. Which salespeople ahve the most orders arriving late compared to their total sales volume?
6. How can we categorize our customers into "Low", "Medium", and "High" value?
7. Which customers have multiple orders in a 5 day period?

## Database used:
[chinook.db](https://github.com/ns102030/Music_Store_Analysis_Using_SQL/blob/main/Music%20Store%20Database%20Analysis%20Using%20SQL/chinook.db)

## Database diagram:

We will be using this diagram in order to help visualize the various joins needed to create the queries to answer our questions. The rows with keys next to the column name represent the primary keys of each table. The lines connect the foreign keys of a table to the primary key of the other table.
