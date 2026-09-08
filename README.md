# FreshMart Sales Analytics

End-to-end retail analytics project focused on cleaning, validating, and analyzing FreshMart's sales data to generate actionable business insights.

## Project Objective

Analyze retail transactions, products, stores, customers, regions, and returns to understand:

- Sales and transaction trends
- Product and brand performance
- Store performance
- Customer segments
- Regional purchasing patterns
- Product and store return rates

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains **8 relational tables** and approximately **289K raw records**, including:

| Table | Rows |
|---|---:|
| Calendar | 730 |
| Regions | 109 |
| Stores | 24 |
| Returns | 7,087 |
| Customers | 10,281 |
| Transactions 1997 | 86,837 |
| Transactions 1998 | 182,883 |
| Products | 1,560 |

The two transaction tables contain **269,720 transaction records** combined.

## Key Insights

- **November and December** consistently recorded the highest transaction volumes, while February was among the lowest.
- **Prime Select** led brands with approximately **58K units sold**, followed by Farmhouse Select and Everyday Basics.
- **Deluxe Supermarkets** were the strongest-performing store type by quantity sold.
- **Midwest** was the highest-volume region, with Des Moines, Omaha, and San Antonio among the leading districts.
- Store size showed a strong relationship with transaction volume: **total_sqft correlation = 0.9695**.
- **Silver Creek Gourmet Pork Chops** had the highest product return rate at approximately **14.1%**.
- The **$50K–$70K income group** and **Bronze membership segment** generated the highest total revenue within their respective categories.

## Workflow

```text
Raw Data
   ↓
Data Inspection
   ↓
Data Cleaning & Standardization
   ↓
Data Validation
   ↓
Exploratory Data Analysis
   ↓
Business Questions
   ↓
Insights & Recommendations
```

### Data Cleaning

Key data-quality issues included inconsistent date formats, data types, categorical values, missing values, and invalid relationships between tables.  
A custom date parser was developed to correctly handle mixed date formats, and data types were standardized across related tables.

### Analytical Validation

The project also documented analytical errors and corrections, including incorrect aggregation grain for store-size analysis and cartesian joins when calculating return rates.

## Project Reports

- **Data Cleaning Report** — data quality issues and cleaning decisions
- **EDA Report** — business questions, visualizations, and insights
- **Challenges & Corrections Log** — technical and analytical issues identified and resolved

## Outcome

This project demonstrates an end-to-end approach to transforming messy retail data into **validated analysis and business-focused insights**, with emphasis on data quality and analytical correctness.
