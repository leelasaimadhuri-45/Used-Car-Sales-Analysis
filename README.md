
# Used Cars Price Analysis

## Project Overview
This project analyzes used car listings from multiple Indian cities to understand pricing patterns, fuel preferences, model year trends, and the effect of distance driven on resale value. The goal is to help identify the key factors influencing used car prices and support data-driven decision-making for buyers, sellers, and marketplaces.

The project combines **Python for data collection and preprocessing** and **Power BI for dashboard visualization**.

---

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- Web Scraping / Data Collection
- Power BI
- Excel / CSV

---

## Dataset
The dataset was collected for multiple cities and stored in separate files:

- `carsmumbai.csv`
- `carsHyd.csv`
- `carsblr.xlsx`
- `carsdelhi.xlsx`

### Source
Used car listings collected from online marketplace data.

### Main Fields
The datasets include columns such as:

- Car Name / Model
- Brand Name
- Model Year / Manufacturing Year
- Distance Driven
- Fuel Type
- Price

---

## Project Workflow

### 1. Data Collection
Used Python in Jupyter Notebook to collect and export car listing data.

Example preprocessing steps included:
- Extracting numeric values from price
- Cleaning distance driven values
- Exporting cleaned files into CSV format

---

### 2. Data Cleaning & Standardization
Since datasets from different cities had slightly different column names and formats, the data was standardized before analysis.

Examples:
- Converted price values into numeric format
- Standardized distance driven values
- Unified model year / manufacturing year columns
- Cleaned fuel type categories

---

### 3. Exploratory Analysis
The analysis focused on answering questions such as:

- Which brands have the highest average resale price?
- How does car age affect price?
- Does distance driven reduce resale value?
- Which fuel types dominate the used car market?
- Which city has higher used car prices?

---

### 4. Power BI Dashboard
A Power BI dashboard was created to visualize pricing and market trends across cities.

---

## Dashboard Highlights

### Key KPIs
- Average Car Price
- Total Listings
- Average Distance Driven
- Average Model Year

### Visuals Included
- Price by Brand
- Price by Fuel Type
- Listings by City
- Distance Driven vs Price
- Model Year vs Average Price
- Brand-wise car count
- City-wise comparison of used car prices

---

## Key Insights
- Car price generally decreases as **distance driven increases**.
- **Newer model years** tend to have higher resale prices.
- Certain brands maintain **stronger resale value** than others.
- Fuel type influences price trends, with some fuel categories showing higher average values.
- Pricing varies across cities, indicating different used car market dynamics.

---

## Business Value
This project helps:

- Buyers compare pricing trends before purchase
- Sellers understand factors affecting resale value
- Used car marketplaces identify high-demand brands and models
- Analysts study pricing behavior across cities

---

## Files in This Repository
- `Cars Analysis.pbix` → Power BI dashboard
- `Project Code.ipynb` → Python data collection and preprocessing notebook
- `DataSet/` → source datasets for different cities
- `Used Cars Price Analysis.docx` → project documentation
- `USED CARS PRICE.pptx` → project presentation

---

