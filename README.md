# Sales Analyzer Notebook

This Jupyter Notebook analyzes product sales data from a CSV file (`productSales.csv`).  
It provides insights such as total products, items sold, revenue, top-selling products, and visualizations.

## Features

- Loads and displays sales data from a CSV file
- Counts total products and items sold
- Calculates total monthly revenue
- Shows revenue and units sold by date
- Identifies top-selling product and highest revenue day
- Visualizes daily revenue and sales with bar charts

## How to Use

1. **Install requirements:**
   ```
   pip install pandas
   pip install matplotlib
   ```

2. **Place your sales data file**  
   Make sure `productSales.csv` is in the same folder as the notebook.

3. **Open the notebook:**
   ```
   jupyter notebook salesAnalizer.ipynb
   ```
   or open it in VS Code.

4. **Run the cells** one by one to see the analysis and charts.

## Output Examples

- **Total Products:** Number of unique products sold
- **Total Items Sold:** Sum of all units sold
- **Total Revenue:** Sum of all revenue
- **Top Selling Product:** Product with the highest units sold
- **Highest Revenue Date:** Date with the most revenue
- **Charts:** Bar charts for daily revenue, daily unit sales, and monthly product sales

## Requirements

- Python 3.x
- pandas
- matplotlib

## Notes

- Make sure your `productSales.csv` has columns: `ProductName`, `UnitsSold`, `TotalRevenue`, `Date`
- This notebook is for educational and analytical purposes.

---

*Created for sales data analysis using Python and
