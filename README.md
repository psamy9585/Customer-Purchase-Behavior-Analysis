# 📊 Customer Purchase Behavior and Sales Performance Analysis

## 📌 Project Overview

This project focuses on analyzing customer purchase transactions to understand sales performance, customer buying behavior, product performance, payment preferences, and revenue generation patterns.

Using **Microsoft Excel and Power BI**, I performed data cleaning, data preparation, DAX calculations, and interactive dashboard development to transform raw customer purchase data into meaningful business insights.

This project demonstrates my practical skills as an **Aspiring Data Analyst** in data preprocessing, data analysis, visualization, and business reporting.

## 🎯 Project Objectives

- Calculate total sales revenue and quantity sold.
- Identify top-selling products based on revenue.
- Analyze product category-wise sales performance.
- Understand customer purchasing behavior.
- Evaluate customer payment method preferences.
- Analyze monthly sales trends.
- Monitor customer review ratings.
- Identify high-value customers.
- Develop an interactive Power BI dashboard for business insights.

## 📂 Dataset Information

**Dataset Name:** Customer Purchase History

**Source:** [TrumpExcel Sample Data](https://trumpexcel.com/excel-sample-data/)

**Domain:** Retail / Sales Analytics

### Dataset Attributes

| Column Name | Description |
|---|---|
| Customer ID | Unique customer identifier |
| Customer Name | Customer name |
| Product | Purchased product |
| Product Category | Product category |
| Purchase Date | Date of purchase |
| Quantity | Number of units purchased |
| Unit Price | Price per unit |
| Total Price | Total purchase amount |
| Payment Method | Payment method used |
| Review Rating | Customer rating |

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data review and preparation |
| Power BI Desktop | Dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | Calculated columns and measures |
| GitHub | Project documentation and portfolio presentation |

## 🔄 Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Data Transformation using Power Query
4. Data Modeling
5. DAX Measures and Calculated Columns
6. Data Analysis
7. Dashboard Development
8. Business Insights and Recommendations

## 🧹 Data Cleaning and Preprocessing

The following data preparation activities were performed:

- Reviewed column names and dataset structure.
- Checked data types and corrected formatting.
- Checked for missing values and duplicate records.
- Identified inconsistent text values.
- Validated date and numerical formats.
- Standardized dataset formatting.
- Prepared the cleaned dataset for Power BI.
- Loaded the prepared data into Power BI.

## 📐 Data Modeling and DAX

The project uses a single purchase table named `Customer_Purchases`.

Since the dataset contains one table, no table relationships were required.

### Calculated Columns

```DAX
Purchase Year =
YEAR(Customer_Purchases[PurchaseDate])
```

```DAX
Purchase Month =
FORMAT(Customer_Purchases[PurchaseDate], "MMM")
```

```DAX
Month Number =
MONTH(Customer_Purchases[PurchaseDate])
```

```DAX
Purchase Year Month =
FORMAT(Customer_Purchases[PurchaseDate], "YYYY-MM")
```

### DAX Measures

```DAX
Total Sales =
SUM(Customer_Purchases[TotalPrice])
```

```DAX
Total Quantity =
SUM(Customer_Purchases[Quantity])
```

```DAX
Total Customers =
DISTINCTCOUNT(Customer_Purchases[CustomerID])
```

```DAX
Total Products =
DISTINCTCOUNT(Customer_Purchases[Product])
```

```DAX
Average Rating =
AVERAGE(Customer_Purchases[ReviewRating])
```

```DAX
Average Unit Price =
AVERAGE(Customer_Purchases[UnitPrice])
```

```DAX
Highest Purchase =
MAX(Customer_Purchases[TotalPrice])
```

```DAX
Lowest Purchase =
MIN(Customer_Purchases[TotalPrice])
```

## 📊 Power BI Dashboard

The dashboard contains the following visualizations:

| Visualization | Purpose |
|---|---|
| KPI Cards | Total Sales, Total Customers, Total Quantity, Average Rating |
| Clustered Column Chart | Sales by Product Category |
| Bar Chart | Top 5 Products by Total Sales |
| Line Chart | Monthly Sales Trend |
| Donut Chart | Sales by Payment Method |
| Bar Chart | Top Customers by Sales |
| Column Chart | Average Rating by Product Category |
| Slicers | Purchase Date, Product Category, Product, Payment Method, Customer Name |

## 🔍 Four Types of Data Analysis

### 1. Descriptive Analysis

Descriptive analysis explains what happened in the business using historical data.

Key metrics analyzed:

- Total sales revenue
- Total customers
- Total quantity sold
- Product category sales
- Product-wise sales
- Monthly sales trends
- Customer ratings

### 2. Diagnostic Analysis

Diagnostic analysis helps understand differences and patterns in business performance.

Key observations:

- Office Supplies generates the highest category sales.
- Tablet generates the highest sales value among product labels.
- Sales contributions differ across payment methods.
- Product categories show different sales performance and customer ratings.

### 3. Predictive Analysis

Predictive analysis explores possible future business performance based on historical patterns.

In this project, the dataset covers January to June 2025.

An assumption-based scenario considers the second half of the year performing similarly to the first half.

**Note:** This is an assumption-based analysis and not a formal forecasting model.

### 4. Prescriptive Analysis

Prescriptive analysis provides recommendations to improve business performance.

Recommendations:

- Maintain availability of products that contribute strongly to sales.
- Investigate lower-sales categories and products before changing pricing or marketing strategies.
- Review customer ratings to identify potential service or quality improvements.
- Test customer retention activities and monitor repeat-customer behavior.
- Collect additional information such as inventory, product costs, promotions, and customer feedback for better decision-making.

## 📈 Key Business Insights

| KPI | Result |
|---|---:|
| Purchase Records | 1,800 |
| Distinct Customers | 1,642 |
| Total Sales | 3,266,656.80 |
| Total Quantity Sold | 8,260 |
| Average Review Rating | Approximately 3.00 / 5 |

### Category-Wise Sales Performance

| Product Category | Total Sales |
|---|---:|
| Office Supplies | 1,133,462.57 |
| Furniture | 1,083,282.25 |
| Electronics | 1,049,911.98 |

### Key Findings

- Office Supplies achieved the highest sales among the three product categories.
- Tablet recorded the highest product sales value of 533,091.00.
- The business generated total sales of 3,266,656.80.
- The dataset contains 1,642 distinct customers.
- The average customer review rating was approximately 3.00 out of 5.
- Monthly sales and payment preferences can be explored interactively through the dashboard.

## 💡 Skills Demonstrated

- Microsoft Excel
- Data Cleaning and Preprocessing
- Power Query
- Data Transformation
- DAX
- Power BI Dashboard Development
- KPI Analysis
- Data Visualization
- Business Intelligence
- Customer Purchase Analysis
- Sales Performance Analysis
- Data Storytelling

## 🏁 Conclusion

This project demonstrates an end-to-end data analytics workflow using Microsoft Excel and Power BI.

By performing data cleaning, transformation, DAX calculations, and interactive dashboard development, I converted customer purchase data into meaningful business insights.

