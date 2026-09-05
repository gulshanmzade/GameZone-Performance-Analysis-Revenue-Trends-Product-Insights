# GameZone-Performance-Analysis-Revenue-Trends-Product-Insights

# GameZone Sales Analysis

## Project Overview
An end-to-end data cleaning and exploratory data analysis (EDA) project evaluating **$6.15M** in transactional revenue for GameZone (a fictional gaming e-commerce company). The analysis covers **20,000+ records** spanning **Jan 2019 – Feb 2021** to surface key sales trends, product performance, and regional drivers for executive stakeholders.

---

## Data Cleaning & Integrity
* **Standardized Formats:** Resolved inconsistent purchase date formats using custom parsing functions.
* **Handled Missing Data:** Imputed missing `Marketing Channel` and `Account Method` fields as `"Unknown"` to avoid revenue bias.
* **Documented Unsolvable Issues:** Identified 2,000 records (~10%) where ship dates preceded purchase dates—flagged as a warehouse log sync issue rather than deleting valuable transaction data.
* **Lookup Mapping:** Corrected corrupt country-to-region codes using a clean reference lookup table.

---

## Key Business Takeaways
* **Top Revenue Drivers:** The *27in 4K Gaming Monitor*, *Nintendo Switch*, and *PS5 Bundle* account for the vast majority of total sales.
* **Holiday Seasonality:** Revenue consistently surges in **Q4** (peaking around ~$500K/month) followed by an early Q1 dip.
* **Data Boundary:** Dataset record collection ends in **February 2021** (108.1K raw records / ~21.8K distinct orders analyzed).

---

## 🛠 Tech Stack & Tools
* **Excel / Power Query:** Data cleaning, pivot table modeling.
* **Power BI:** Dynamic dashboard (*Sales Performance Dashboard*).
