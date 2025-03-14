# Sales-Dashboard-Project
This project involves building a Sales Dashboard for a Supermarket Shop to analyze key business metrics like total sales, total profit, sales trends, product performance, and category distribution. The dashboard was developed using Excel with data cleaning, analysis, and visualization techniques.
 Dataset Cleaning & Preprocessing

## 🛠 Steps Taken:

 - Loaded the dataset into Excel and examined the structure (rows, columns, missing values, duplicates).

- Removed duplicates using:

- Data -> Remove Duplicates

- Handled missing values by:

- Replacing empty values in numeric columns with 0 or interpolating where necessary.

- Standardized data formats:

- Dates formatted as YYYY-MM-DD

- Currency values properly formatted.

- Created new calculated columns, such as:

- Profit: = Sales - Cost

- Profit %: = (Profit / Sales) * 100

### 📊 Data Analysis (Formulas & Calculations)

- Several formulas and pivot tables were used:

- Total Sales Calculation: =SUM(Sales)

- Total Profit Calculation: =SUM(Profit)

- Profit Percentage: = (Total Profit / Total Sales) * 100

- Monthly Sales Trend: Using a Pivot Table with SUM(Sales) grouped by Month

- Product Performance Ranking: =RANK(E2, E:E, 0) to rank products by sales

## 📈 Dashboard Creation Process

- Data Visualization with Pivot Charts

- Monthly Sales & Profit Trend (Clustered Column Chart)

- Daily Sales Performance (Line Chart)

- Sales Type Breakdown (Pie Chart for Direct, Online, Wholesale Sales)

- Payment Mode Distribution (50% Cash / 50% Online - Pie Chart)

- Top-Selling Products & Categories (KPI Indicators)

- Conditional Formatting to highlight key trends:

- Used Color Scales to visually represent high and low sales values.

- Interactive Elements:

- Dropdowns for selecting Year and Month.

- Slicers for filtering based on Product Category and Payment Mode.

#📌 Final Insights & Conclusion

## Total Sales: $4,01,412

## Total Profit: $68,908

## Profit Margin: 21%

## Top Product: Product41 - $22,952

## Top Category: Category04 - $95,269

Sales Type Distribution:

### 52% Online Sales

### 33% Wholesale Sales

### 15% Direct Sales

## 🔥 Key Business Takeaways:

Online sales contribute the highest percentage (52%), suggesting more investment in e-commerce.

Category04 generates the highest revenue, so more promotions could be targeted at this category.

Profit margins could be improved by optimizing product costs and targeting high-margin items.

