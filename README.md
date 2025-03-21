# E-commerce-Marketing-Insights

## Introduction
In the dynamic world of business, answering key questions is essential for driving growth and strategy. This project leverages the [Kaggle E-commerce Marketing Insights](https://www.kaggle.com/datasets/rishikumarrajvansh/marketing-insights-for-e-commerce-company) datasets to explore common business challenges and trends. The analysis will cover crucial areas such as revenue and retention trends, cohort behavior, the impact of discounts on pricing, and customer segmentation. Additionally, more advanced techniques—including lifetime value (LTV) forecasting, cross-selling analysis, and predicting the next purchase date—will be employed to provide deeper insights into customer behavior and business performance.

## Data
**Online_Sales.csv:** This file contains actual order data (point of Sales data) at the transaction level with
below variables.
- CustomerID: Customer unique ID
- Transaction_ID: Transaction Unique ID
- Transaction_Date: Date of Transaction
- Product_SKU: SKU ID – Unique Id for product
- Product_Description: Product Description
- Product_Cateogry: Product Category
- Quantity: Number of items ordered
- Avg_Price: Price per one quantity
- Delivery_Charges: Charges for delivery
- Coupon_Status: Any discount coupon applied

 
**Customers_Data.csv:** This file contains customer’s demographics.
- CustomerID: Customer Unique ID
- Gender: Gender of customer
- Location: Location of Customer
- Tenure_Months: Tenure in Months

**Discount_Coupon.csv:** Discount coupons have been given for different categories in different
months
- Month: Discount coupon applied in that month
- Product_Category: Product category
- Coupon_Code: Coupon Code for given Category and given month
- Discount_pct: Discount Percentage for given coupon

**Marketing_Spend.csv:** Marketing spend on both offline & online channels on day wise.
- Date: Date
- Offline_Spend: Marketing spend on offline channels like TV, Radio, NewsPapers, Hordings etc…
- Online_Spend: Marketing spend on online channels like Google keywords, facebook etc..


**Tax_Amount.csv:** GST Details for given category
- Product_Category: Product Category
- GST: Percentage of GST


## v0.1.0 (21/03/2025)
| Date | Updates | 
|----------|----------|
| 2025.03.21   | Completed basic exploratory analysis & Customer Segmentation  | 
