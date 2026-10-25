# Power BI Assignment 1 – Data Transformation and Data Modeling

## 📌 Project Overview
This project demonstrates data cleaning, transformation, data merging, aggregation, and relationship management using Microsoft Power BI and Power Query Editor.

## 🎯 Objectives
- Import CSV files into Power BI.
- Clean and transform data using Power Query Editor.
- Create custom and conditional columns.
- Merge tables using Order ID.
- Identify missing values and apply filters.
- Perform aggregations to summarize business data.
- Establish relationships between tables in the data model.

## 📂 Dataset
The assignment uses the following datasets:
- **List of Orders.csv**
- **Order Details.csv**
- **Sales Target.csv**

## 🛠️ Tasks Performed

### 1. Data Import
- Imported the CSV files into Power BI.
- Opened the tables in Power Query Editor.

### 2. Data Transformation
- Restricted the List of Orders table to the first 500 rows.
- Changed Order Date to the Date data type.
- Changed Amount and Target to Fixed Decimal Number.
- Converted Customer Name to proper case.

### 3. Custom Columns
- Created a Location column by combining City and State.
- Created a Profit Margin column using Profit / Amount, expressed as a percentage.
- Created a Profit Status column:
  - Profit < 0: Loss
  - Profit = 0: Break-Even
  - Profit > 0: Profit

### 4. Merge Tables
- Merged List of Orders and Order Details using Order ID.
- Named the merged output table Orders Data.

### 5. Data Quality
- Identified missing values across the tables.
- Sorted Orders Data by Order Date in descending order.
- Applied filters to analyze orders by state.

### 6. Data Aggregation
Created summaries for:
- Count of Order ID
- Average Profit by Category
- Total Amount by Sub-Category
- Total Target by Month of Order Date

### 7. Data Modeling
Established relationships between tables using the relevant columns, including:
- List of Orders and Order Details using Order ID.
- Order Details and Sales Target using Category.

## 💻 Tools Used
- Microsoft Power BI Desktop
- Power Query Editor
- GitHub

## 📸 Screenshots and Documentation
Screenshots documenting the assignment steps and results are included in the project documentation.

## 📚 Learning Outcomes
- Understanding data cleaning and transformation.
- Creating custom and conditional columns.
- Merging tables and performing aggregations.
- Understanding relationships and data modeling in Power BI.



**Project:** Power BI Assignment 1  
**Topic:** Data Transformation and Data Modeling
