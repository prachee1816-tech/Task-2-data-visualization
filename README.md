# Task 2: Data Visualization and Storytelling

**Dataset:** Superstore sales data (`Superstore.csv`, 9,994 order lines, 2014-2017)
**Tools:** Python (pandas, matplotlib). Tableau / Power BI are not available on my phone setup, so the same dashboard-style charts were built in Python.
**Deliverable:** `Superstore_Visual_Report.pdf` (6-page visual report with summary storyboard)

## Story
Sales grew 51% from 2014 to 2017 and profit nearly doubled, but discounting is eating profit.

## Key insights
1. Sales and profit grow every year; September to December are the peak months (November is the biggest).
2. Furniture earns only 2.5% margin; Tables, Bookcases and Supplies lose money.
3. Discounts above 20% turn sales into losses (about $135K lost in total).
4. The Central region has the lowest margin (7.9%); the West has the highest (14.9%).

## Charts included
- KPI summary and storyboard
- Sales and profit by year, sales by month
- Profit by sub-category (losses in red)
- Profit margin by discount band
- Sales and profit margin by region
- Recommendations

## Files
- `Superstore_Visual_Report.pdf` - final report
- `charts/` - each page as an image (screenshots)
- `create_report.py` - code that builds the charts and report
- `Superstore.csv` - dataset

## How to run
`pip install pandas matplotlib` then `python create_report.py`
