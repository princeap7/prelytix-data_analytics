# Day 9 - Data Cleaning, Transformation & Introduction to Power BI

## Overview

Day 9 focused on learning **Data Cleaning**, **Data Transformation**, and basic **Power BI & DAX** concepts using Power Query and sales datasets for analytical reporting.

---

# Topics Learned

## Data Cleaning Process

* Using First Row as Header
* Changing Data Types
* Removing Unnecessary Columns
* Removing Duplicates
* Removing Blank Values
* Replacing Values
* Text Cleaning Techniques

---

## Data Transformation

* Creating Custom Columns
* Business Logic Transformations
* Sales Calculations
* Quarter & Month Extraction

---

## Power BI & DAX

* Loading Data into Power BI
* Creating Basic DAX Measures
* Revenue Calculations

---

# Practical Tasks Performed

## Data Cleaning Tasks

1. Use First Row as Header
2. Change Data Types according to data
3. Remove unnecessary columns
4. Remove duplicate records
5. Remove blank values (if present)
6. Replace values in Country column
7. Perform text cleaning using:

   * TRIM
   * UPPER

---

## Data Transformation Tasks

1. Add “Shipment Size” column based on Boxes Shipped:

   * Big Cargo
   * Medium Cargo
   * Small Cargo

2. Add Delivery Cost column:

   * $3 per box

3. Calculate Total Quantity Sold:

   * 10 quantity per box

4. Calculate Total Sales

5. Add Quarter column

6. Add Month column

7. Load transformed data into Power BI

---

## DAX Measures Created

1. Total Sales

```DAX
Total Sales = SUM('Sheet1'[Amount])
```

2. Revenue Per Box

```DAX
Revenue Per Box = DIVIDE(SUM('Sheet1'[Amount]), SUM('Sheet1'[Boxes Shipped]))
```

---

# Tools & Technologies Used

* Microsoft Excel
* Power Query
* Power BI
* DAX
* Data Cleaning Techniques
* Data Transformation

---

# Learning Outcome

By the end of Day 9, I learned:

* Cleaning raw datasets efficiently
* Transforming business data using Power Query
* Creating calculated columns
* Loading data into Power BI
* Writing basic DAX measures
* Preparing datasets for reporting and dashboarding

---

# Author

**Prince Patel**

B.Tech Student | Aspiring Data Analyst

**Date:** 22-05-2026
