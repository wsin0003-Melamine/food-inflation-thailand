# Thailand Food Inflation Analysis

## Project Overview

This project analyzes food price trends and inflation in Thailand between 2000 and 2020 using food price and inflation datasets.

The objective is to explore how inflation may influence food prices across different food categories.

## Dataset

Data sources:
- World Food Programme Food Prices Dataset
- World Bank Inflation Dataset

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
food-inflation-thailand/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebook/
│   ├── 01_data_cleaning.ipynb
│   └── 02_eda_analysis.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore

## Analysis Performed

- Data cleaning and preprocessing
- Inflation dataset reshaping
- Food price trend analysis
- Inflation vs food price comparison
- Correlation analysis
- COVID-19 impact comparison

## Key Insights

- Staple food prices showed stable long-term growth trends.
- Chicken prices were significantly higher and more volatile than staple foods.
- Inflation rates appeared to have a moderate positive relationship with food prices.
- Food price distributions shifted upward after COVID-19.

## Future Improvements

- Build an interactive Streamlit dashboard
- Add food price forecasting models
- Automate data pipelines
- Integrate SQL database storage

## How to Run

Clone the repository:

git clone <https://github.com/wsin0003-Melamine/food-inflation-thailand.git>

Install dependencies:

pip install -r requirements.txt

