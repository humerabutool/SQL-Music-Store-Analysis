# SQL-Music-Store-Analysis

# Project Description: Music Store Analysis Using MySQL

# Overview:

This project involves a comprehensive analysis of a music store's dataset using MySQL. The dataset, loaded into MySQL, comprises 11 interconnected tables: album, track, playlist, invoice, invoice_line, genre, artist, customer, media, and playlist_track. The objective of this project is to derive meaningful insights and patterns from the data to inform business decisions and strategies.

# Objectives:

Data Integration: Efficiently load and integrate the music store dataset into MySQL.
Data Exploration: Perform exploratory data analysis to understand the structure and content of each table.
Complex Queries: Utilize SQL commands such as SELECT, FROM, WHERE, and various types of JOINs (INNER JOIN, LEFT JOIN, etc.) to merge and retrieve relevant data across multiple tables.
Common Table Expressions (CTE): Implement CTEs for complex query structuring, enhancing readability and maintainability.
Business Insights: Answer key business questions and generate reports on sales trends, customer behavior, popular genres, and more.

# Methodology
Data Loading: The dataset was imported into MySQL, establishing the relationships between the tables through foreign keys.

Exploratory Data Analysis:
Examined each table to understand its columns and relationships.
Identified key attributes for analysis, such as sales data, customer demographics, and track information.

# SQL Queries:

Basic Queries: Retrieved data using basic SELECT statements.

Conditional Retrieval: Applied WHERE clauses to filter data based on specific conditions.

Joins: Used various types of joins to combine data from multiple tables, enabling comprehensive analysis.

Example: Joining invoice, invoice_line, and track tables to analyze sales by track.

Aggregation: Employed aggregation functions (SUM, COUNT, AVG) to summarize data.

Example: Calculating total sales per genre.

CTEs: Used CTEs to break down complex queries into more manageable parts.

Example: Creating a CTE to first retrieve the top-selling tracks, then using it in further analysis to determine contributing factors.

Joins: Used various types of joins to combine data from multiple tables, enabling comprehensive analysis.

Example: Joining invoice, invoice_line, and track tables to analyze sales by track.

Aggregation: Employed aggregation functions (SUM, COUNT, AVG) to summarize data.
Example: Calculating total sales per genre.
CTEs: Used CTEs to break down complex queries into more manageable parts.
Example: Creating a CTE to first retrieve the top-selling tracks, then using it in further analysis to determine contributing factors.
