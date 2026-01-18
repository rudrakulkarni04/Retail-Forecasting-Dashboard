# SuperStore Retail Forecasting & Inventory Dashboard

## Problem Statement
Build a retail decision-support system that forecasts sales for key region-category segments and optimizes inventory levels and stock transfers to reduce stock-outs and excess stock.

## Features
- Data cleaning and EDA on 6000+ SuperStore transactions
- Prophet time-series forecasting for 4 key segments
- Inventory planning: 30-day demand vs current stock
- Stock transfer recommendations between regions
- Power BI dashboard with historical + forecast views

## Project Structure
Retail-Forecasting-Dashboard/
├── data/ # Raw data
├── notebooks/ # Jupyter analysis
├── outputs/ # Clean data + forecasts
└── powerbi/ # Final dashboard


## How to run
1. `pip install -r requirements.txt`
2. Open `notebooks/01_Retail_Forecasting_and_Inventory.ipynb`
3. Run all cells to generate forecasts and outputs
4. Open `powerbi/SuperStore_Dashboard.pbix`

## Results
- Forecasted 30-day demand for West/Technology, West/Furniture, South/Office Supplies, West/Office Supplies
- Identified South/Office Supplies shortage and recommended transfer of 15,616 units from West
- Interactive dashboard shows historical sales + future demand + transfer suggestions
