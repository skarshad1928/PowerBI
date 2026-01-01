# Power BI Assignment – Product Lookup Transformations

## Overview
This repository showcases a Power BI assignment focused on loading and transforming product-related CSV files using Power Query.

The assignment consists of **7 tasks**, all of which have been completed and are included in the Power BI (.pbix) file.

---

## Task Breakdown

### Task 1: Connect to CSV Files
- Connected to:
  - Company Product Categories Lookup.csv
  - Company Product Subcategories Lookup.csv

---

### Task 2: Rename Queries
- Renamed queries to:
  - Product Category Lookup
  - Product Subcategory Lookup

---

### Task 3: Validate Headers and Data Types
- Promoted first row as headers
- Verified correct data types for all columns

---

### Task 4: Create SKU Type Column
- Loaded Company Product Lookup.csv
- Created a new column **SKU Type**
- Extracted characters before the first dash (-) from ProductSKU

---

### Task 5: Update SKU Type Logic
- Modified SKU Type calculation
- Extracted characters before the **second dash (-)**

---

### Task 6: Replace Product Style Values
- Replaced `0` values in Product Style column with `"NA"`
- Updated column data type to Text

---

### Task 7: Load to Data Model
- Applied all transformations
- Loaded data into the Power BI data model

---

## Tools Used
- Power BI Desktop
- Power Query Editor

---

## File Included
- `.pbix` file containing all queries and transformations
