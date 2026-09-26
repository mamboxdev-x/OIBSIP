# Exploratory Data Analysis on Retail Sales Data

**Track:** Data Analytics  
**Program:** Oasis Infobyte Summer Internship Program (OIB-SIP)  
**Task:** Level 1 — Task 1  
**Author:** ADJA Mambo David Eléazar

## Objective

Explore a retail sales dataset to identify temporal patterns, customer demographics, and category performance, then present practical, data-driven recommendations.

## Dataset

The project uses the **Retail Sales Dataset** by Mohammad Talib, obtained from [Kaggle](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset). Kaggle lists the dataset as **CC0: Public Domain**. Source details are in [`data/SOURCE.md`](data/SOURCE.md).

The CSV contains 1,000 transactions and fields for date, customer ID, gender, age, product category, quantity, unit price, and total amount. It does not contain product names/IDs, profit margins, or repeat-purchase history; accordingly, the notebook does not claim to rank individual products or measure profit.

## Analysis

The notebook includes data inspection and validation, descriptive statistics, monthly and quarterly trends, customer demographic summaries, category revenue and transaction comparisons, a numerical correlation heatmap, and a category-by-gender revenue visualization. It discusses dataset limitations and outlines three business recommendations.

## Run locally

From this project directory, install dependencies and start Jupyter:

```bash
pip install -r requirements.txt
jupyter notebook
```

Open `notebooks/retail_sales_eda.ipynb` and run all cells. The notebook expects the dataset at `data/retail_sales_dataset.csv`.

## Project structure

```text
DataAnalytics-L1-EDARetailSales/
├── data/
│   ├── SOURCE.md
│   └── retail_sales_dataset.csv
├── notebooks/
│   └── retail_sales_eda.ipynb
├── README.md
└── requirements.txt
```
