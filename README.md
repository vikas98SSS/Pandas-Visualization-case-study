# vikas dhakad
# Pandas-Visualization-case-study

**Description of pandas visualization case study**

- **Data Import and Structure**
  - Libraries used: `pandas`, `numpy`, `matplotlib.pyplot`
  - Data imported from a CSV file containing sales data with columns such as `AccountId`, `AccountName`, `Region`, `Division`, `City`, `State`, `Tier`, `Month`, `Sales2015`, `Sales2016`, `Units2015`, `Units2016`, `TargetAchieved2015`, and `TargetAchieved2016`.

- **Data Analysis and Visualization**
  - **Sales Comparison (2015 vs 2016)**
    - A pivot table was created to summarize total sales by region for the years 2015 and 2016.
    - A bar chart was plotted to visually compare total sales across regions for both years.

  - **Sales Distribution by Region (2016)**
    - A pie chart was generated to show the distribution of total sales in 2016 by region.

  - **Sales Comparison by Region and Tier**
    - Another pivot table was created to analyze total sales by region and tier for 2015 and 2016.
    - A bar chart was plotted to compare these sales figures.

  - **State-wise Sales Analysis (East Region)**
    - Focused on the East region, a bar chart was created to show sales by state, highlighting states that experienced a decline in sales from 2015 to 2016.

  - **Units Sold by Division (High Tier)**
    - A bar chart was plotted to show the total units sold in 2015 and 2016 for divisions with a high tier.

- **Quarterly Sales Analysis**
  - A new column `Qtr` was added to categorize months into quarters.
  - A pivot table was created to summarize sales by quarter for 2015 and 2016, followed by a bar chart for visual comparison.

- **Sales by Tier and Quarter**
  - Data was filtered to exclude 'Out' tier accounts.
  - A pie chart was created to show the distribution of sales by tier for each quarter.

This case study effectively demonstrates the use of Pandas for data manipulation and Matplotlib for data visualization, providing insights into sales performance across different dimensions.
