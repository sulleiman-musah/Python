# Sales Data Analysis Using Python

## Project Overview
This project analyzes sales and product data using **Python** and the **Pandas** library to demonstrate practical data handling and exploratory analysis skills.  
The analysis explores datasets containing sales transactions and product information, highlighting techniques such as data loading, inspection, cleaning, and summarization.

The goal is to extract insights from raw data and showcase essential Python data analysis capabilities.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Files in Repository](#files-in-repository)  
3. [Journey of the Data](#journey-of-the-data)  
   - [Datasets](#datasets)  
   - [Data Cleaning and Exploration](#data-cleaning-and-exploration)  
4. [Script Functionality](#script-functionality)  
5. [Key Learnings](#key-learnings)  
6. [Recommendations](#recommendations)  
7. [Tools and Technologies](#tools-and-technologies)  
8. [Contact](#contact)  
9. [Acknowledgement](#acknowledgement)

---

## Files in Repository

| File Name | Description |
|------------|--------------|
| `script.ipynb` | Jupyter Notebook containing the analysis code |
| `sales.xlsx` | Dataset containing sales records |
| `products.xlsx` | Dataset containing product information |
| `Project_Documentation - Sales Data Analysis.docx` | Full project documentation |

---

## Journey of the Data

### Datasets
- **sales.xlsx** – Contains individual sales transactions, including product IDs, quantities, and totals.  
- **products.xlsx** – Contains product information such as product ID, name, and category.  

### Data Cleaning and Exploration
- Verified data consistency across both datasets.  
- Checked for null values, duplicates, and data type mismatches.  
- Conducted exploratory analysis to understand data structure and relationships.

---

## Script Functionality

### Import Libraries
- **pandas** – For data analysis and manipulation.  
- **os** – For managing file paths and directories.  

### Load Datasets
```python
import pandas as pd
import os

sales_data = pd.read_excel('sales.xlsx')
products_data = pd.read_excel('products.xlsx')
