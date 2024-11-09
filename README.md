# datavis

**Sales and Temperature Data Analysis**
This project analyzes sales data over time and compares it with temperature data in Astana to explore any correlation between sales and weather conditions.

**Project Overview**
The project involves:
Loading and processing sales data.
Grouping sales data by date to analyze daily sales trends.
Visualizing sales over time.
Identifying outliers and top-selling products under specific conditions.
Merging sales data with temperature data for comparative analysis.


**To run this project, install the following libraries:**
pandas
numpy
matplotlib
seaborn
Install dependencies using pip:

**Data**
Sales Data: A CSV file (data.csv) containing columns like Date, Warehouse, Client, Product, and Quantity.
Temperature Data: Weather data in Excel format (weather-merge.xls), downloaded from rp5.ru.

**Steps**
1. Load Data
Load sales data from data.csv into a DataFrame.
Convert the Date column to datetime format.
2. Data Analysis
Grouping Sales Data: Group data by date and calculate total sales for each day.
Visualization: Plot daily sales to identify trends and seasonal patterns.
Outlier Detection: Detect extreme values in sales to identify anomalies.
Top Product Identification: Identify top products by sales on specific days and months.
3. Merging with Temperature Data
Load and process temperature data.
Group temperature data by date and calculate the average daily temperature.
Merge sales and temperature data into one DataFrame.
4. Visualization
Plot a combined graph to show both sales and temperature trends over time.
Display a separate temperature graph to observe weather trends independently.
Results and Observations
Sales trends show seasonal fluctuations.
Temperature data is compared with sales to explore potential correlations.

**To execute the notebook:**
Ensure all dependencies are installed.
Open python_block.ipynb in Google Colab.
Upload data.csv and weather-merge.xls files in the appropriate cells.
Run each cell sequentially to view outputs and visualizations.
