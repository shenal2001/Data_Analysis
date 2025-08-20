# UK Retail Shop Data Analysis

This project provides a comprehensive data analysis of the [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail), which contains transactional data from a UK-based online retailer. The analysis is performed in a Jupyter Notebook and demonstrates various data cleaning, exploration, and visualization techniques using Python libraries such as pandas and matplotlib.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Usage](#usage)
- [Analysis Steps](#analysis-steps)
- [Results & Insights](#results--insights)
- [References](#references)

## Overview

The goal of this project is to explore and analyze retail transaction data to gain insights into sales trends, customer behavior, and data quality issues. The notebook guides you through the process of:

- Loading and inspecting the dataset.
- Checking for missing values and data types.
- Visualizing and interpreting key statistics of the dataset.

## Dataset

- **Source:** UCI Machine Learning Repository – [Online Retail Data Set](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- **Format:** Excel (`Online Retail.xlsx`)
- **Content:** Transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based online retail.

**Columns:**
- `InvoiceNo`: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction.
- `StockCode`: Product (item) code.
- `Description`: Product (item) name.
- `Quantity`: The quantities of each product per transaction.
- `InvoiceDate`: Invoice date and time.
- `UnitPrice`: Unit price (per product).
- `CustomerID`: Customer number.
- `Country`: Country name.

## Project Structure

```
.
├── UKRetailShop.ipynb  # Main analysis notebook
└── README.md           # Project documentation (this file)
```

## Requirements

- Python 3.x
- Jupyter Notebook (or Google Colab)
- pandas
- matplotlib
- openpyxl (for reading .xlsx files)

Install dependencies using pip:
```bash
pip install pandas matplotlib openpyxl
```

## Usage

1. **Download the Dataset:**
   The notebook automatically downloads the dataset from UCI if run in a compatible environment.

2. **Run the Notebook:**
   Open `UKRetailShop.ipynb` in Jupyter Notebook or Google Colab and execute cells sequentially.

   - To run in Google Colab, click the badge at the top of the notebook or [open in Colab](https://colab.research.google.com/github/shenal2001/Data_Analysis/blob/main/UKRetailShop.ipynb).

3. **Follow the Analysis:**
   The notebook walks through each step, including data loading, cleaning, exploration, and initial visualization.

## Analysis Steps

- **Setup:** Install required libraries.
- **Data Download & Extraction:** Download and unzip the UCI dataset.
- **Data Loading:** Read the Excel file using pandas.
- **Initial Exploration:** View sample data, shape, and data types.
- **Missing Values:** Quantify and display rows with missing values.
- **Data Quality:** Inspect and discuss missing descriptions and customer IDs.

## Results & Insights

- The dataset contains over 540,000 rows and 8 columns.
- Some records have missing values, especially in the `Description` and `CustomerID` columns.
- The notebook identifies and displays all such missing values for further analysis or cleaning.
- Preliminary data exploration sets the stage for deeper insights into customer purchasing behavior and product sales.

## References

- UCI Machine Learning Repository: [Online Retail Data Set](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- [pandas documentation](https://pandas.pydata.org/)
- [matplotlib documentation](https://matplotlib.org/)

---

**Author:** [shenal2001](https://github.com/shenal2001)

Feel free to contribute or raise issues for improvements!
