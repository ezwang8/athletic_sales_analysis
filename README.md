# Athletic Sales Data Analysis

## Project Overview
This program is tasked to analyze U.S. athletic clothing sales data from 2020 to 2021. The goal of this project is to allow users to determine key insights which could majorly impact athletic clothing companies' sales. Findings such as the top-selling cities, best-performing retailers, and sales trends for women's athletic footwear.

## Installation Instructions
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ezwang8/athletic_sales_analysis.git
   ```
   
2. **Ensure Python is installed:**
   Verify Python installation:
   ```bash
   python --version
   ```
   If not installed, download it from [python.org](https://www.python.org/downloads/).

3. **Install Jupyter Notebook:**
   If Jupyter is not installed, run:
   ```bash
   pip install jupyter
   ```

4. **Install pandas Package:**
   Install pandas with:
   ```bash
   pip install pandas
   ```

5. **Navigate to the Project Directory:**
   ```bash
   cd athletic_sales_analysis
   ```

6. **Launch Jupyter Notebook:**
   Open the notebook interface:
   ```bash
   jupyter notebook
   ```

7. **Open the Notebook:**
   In Jupyter, locate the `athletic_sales_analysis.ipynb` file and run the cells for analysis.

## File Roles
- **athletic_sales_analysis.ipynb:** The main script that performs the analysis. It contains the full data analysis process for exploration, transformation, and validation of the dataset.
- **athletic_sales_2020.csv & athletic_sales_2021.csv:** The CSV files, inside the "Resources" folder, which are the data sources used for analysis. Each are separated data based on their designated years, and both share sales data separated into columns. Including various product categories, sales information, and regional data.

## Steps
1. **Combine and Clean the Data:** Merge the two sales data from 2020 and 2021, then check to ensure the data tyes and formats are cleaned and consistent.
2. **Analyze Regional Sales:** Determine which regions are successful in athletic clothing sales by finding which sold the most products and made the most sales.
3. **Identify Top Retailers:** Find the top retailers by checking which had the highest total sales, then narrowing the search to which sold the most women's athletic footwear.
4. **Sales Trends by Day and Week:** Adjust the focus to invoice date to determine which days and weeks had the the highest sales of women's athletic footwear.

## Summary of Findings
This analysis revealed the following key insights in the athletic clothing market:
- The top-selling region were primarily in metropolitan areas. Including New York, San Francisco, and Miami.
- West Gear, Food Locker, and Kohl's were leading the market for women's athletic footwear, with significant sale numbers compared to the other competitors.
- Day-of-week trends showed higher sales during weekends. Weekly trends showed seasonal peaks during major sports events, especially during Mid-December and Mid-July.
