# E-commerce Sales Data Analysis & EDA

## Project Overview
Exploratory data analysis of e-commerce sales data using Python to identify sales trends, product performance, customer purchasing patterns, payment preferences, and order-status trends.

## Tools & Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Google Colab / Jupyter Notebook

## Dataset
- Cleaned dataset: 49,222 rows and 17 columns
- Order dates: January 2024 – June 2026
- Original source files included for data-quality investigation

## Key Analysis Areas
- Monthly sales and order trends
- Product and category performance
- Customer segments and city-level sales
- Payment-method analysis
- Discount patterns
- Order-status analysis
- Data-quality validation

## Data Quality Notes
- Nineteen rows contain negative quantities and negative sales; their business meaning requires confirmation.
- 778 source order IDs are absent from the cleaned dataset. The exact exclusion rule is unknown.
- Recorded sales do not consistently match a single confirmed calculation formula.
- Sales associated with cancelled or returned orders should not automatically be interpreted as confirmed losses or refunds.

## Project Structure
- `data/` — cleaned dataset and four original CSV files
- `notebooks/` — exploratory data analysis notebook

## How to Run
1. Download or clone this repository.
2. Install `pandas`, `numpy`, `matplotlib`, and `seaborn`.
3. Open `notebooks/ecommerce_sales_eda.ipynb` in Jupyter Notebook or Google Colab.
4. Ensure the notebook's data paths match the repository structure before running all cells.

## Project Purpose
Demonstrates exploratory data analysis, data validation, visualization, and analytical interpretation for a Data Analyst portfolio.
