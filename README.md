# 📊 Flipkart Sales & Delivery Performance Dashboard

## 📌 Project Overview

This project is an Excel-based Sales & Delivery Performance Dashboard created using a Flipkart sales dataset.

The main purpose of this dashboard is to understand sales performance, customer orders, cancellations, payment-method behavior, product performance, and delivery trends across different regions.

I built this dashboard to turn raw sales data into simple and useful business insights that can help identify problem areas and improvement opportunities.

---

## 🎯 Business Questions

The dashboard was created to answer questions such as:

- Which categories perform well across different regions?
- Which payment methods have higher cancellation rates?
- Which regions are performing better or worse in terms of sales?
- How is delivery performance changing over time?
- Which products generate the highest sales?
- How are monthly order volumes changing?

---

## 📊 Dashboard KPIs

The dashboard currently shows:

- **Total Revenue:** ₹17,47,718.25
- **Total Orders:** 1,000
- **Total Customers:** 1,000
- **Cancellation Rate:** 32.00%
- **Fast Delivery:** 28.97%

---

## 📈 Dashboard Analysis

### 1. Sales Performance by Category & Region

The category and region comparison shows noticeable differences in sales performance.

- **Home** is one of the stronger-performing categories across the regions.
- **Electronics** also shows strong sales across multiple regions.
- Category performance is not the same across every region, which means regional strategies can be useful instead of using one common approach.

### 2. Cancellation Rate by Payment Method

The payment-method analysis shows differences in cancellation rates:

- **UPI:** 23.44%
- **Debit Card:** 20.94%
- **Credit Card:** 20.63%
- **Net Banking:** 18.75%
- **COD:** 16.25%

UPI has the highest cancellation rate in the current analysis, while COD has the lowest.

This suggests that payment-method behavior should be monitored when investigating order cancellations.

### 3. Regional Sales Performance

The regional sales chart shows:

- **South:** ₹4,66,925.26
- **North:** ₹4,50,391.09
- **East:** ₹4,36,837.07
- **West:** ₹3,93,564.83

The **West region has the lowest sales** among the four regions, while South records the highest sales.

### 4. Delivery Performance

The delivery trend compares Fast and Slow deliveries across the available months.

The dashboard shows that **Slow deliveries are consistently higher than Fast deliveries**.

Overall, only **28.97% of completed orders are classified as Fast deliveries**, indicating that delivery speed is an area that needs attention.

### 5. Top 5 Products by Sales

The dashboard identifies the five products contributing the highest sales:

- Product_35
- Product_28
- Product_46
- Product_15
- Product_13

**Product_35** has the highest sales among the top five products shown in the dashboard.

### 6. Monthly Order Trend

The monthly order trend shows:

- January: ~255 orders
- February: ~218 orders
- March: ~260 orders
- April: ~258 orders
- May: ~10 orders

There is a sharp decline in May compared with the previous months.

This could be worth investigating further to determine whether it is related to demand, data availability, or another business factor.

---

## 💡 Key Insights

Based on the dashboard analysis:

1. The overall **cancellation rate is 32%**, meaning cancellations are a significant part of the order data.

2. **UPI has the highest cancellation rate (23.44%)** among the payment methods shown.

3. **South generates the highest regional sales**, while West has the lowest sales.

4. **Fast deliveries account for only 28.97% of completed orders**, while slow deliveries make up the larger share.

5. **Home and Electronics** show strong category-level sales across the regions.

6. **Product_35** is the highest-selling product among the displayed top five products.

7. The monthly trend shows a **major drop in orders in May**, which should be investigated before making business decisions.

---

## 🚀 Recommendations

### 1. Reduce Order Cancellations

Since the overall cancellation rate is 32%, Flipkart could investigate the major reasons behind cancellations.

Possible areas to check:
- Payment failures
- Customer-initiated cancellations
- Stock availability
- Delivery delays
- Order confirmation issues

### 2. Investigate UPI Cancellations

UPI has the highest cancellation rate in this dataset.

The business could analyze UPI transactions further to identify whether payment failures, order confirmation delays, or other factors are contributing to cancellations.

### 3. Improve Delivery Speed

Since slow deliveries are much higher than fast deliveries, logistics performance should be reviewed.

Possible actions include:
- Improving inventory placement
- Optimizing delivery routes
- Reviewing courier performance
- Improving warehouse allocation
- Focusing on regions with higher delivery delays

### 4. Focus on the West Region

West has the lowest regional sales in the dashboard.

The business could investigate:
- Product demand
- Inventory availability
- Customer preferences
- Delivery coverage
- Regional promotions

### 5. Learn From High-Performing Products

Products such as Product_35 and Product_28 are among the top sellers.

Their category, pricing, availability, and customer demand can be analyzed to understand what is driving their performance.

### 6. Investigate the May Order Drop

The sudden decline in May orders should not immediately be treated as a business decline.

It would be useful to check whether:
- The dataset contains fewer May records
- There was a seasonal effect
- There were inventory issues
- There was a campaign or operational change
- The data collection period was incomplete

---

## 🛠️ Tools & Skills Used

- **Microsoft Excel**
- Pivot Tables
- Pivot Charts
- Slicers
- Excel formulas
- Data cleaning and transformation
- KPI creation
- Data visualization
- Business analysis
- Dashboard design

---

## 📊 Dashboard Features

The dashboard includes:

- KPI cards
- Region slicer
- Category slicer
- Payment Method slicer
- Category vs Region analysis
- Payment Method cancellation analysis
- Regional sales comparison
- Delivery performance trend
- Top 5 products by sales
- Monthly order trend

---

## 📁 Dataset Structure

The main dataset contains information related to:

- Order details
- Customer information
- Product information
- Order and delivery dates
- Cancellation dates
- Region
- Category
- Payment method
- Delivery status
- Sales amount
- Delivery performance

Master data was also used for customer, product, and regional information.

---

## 🎓 Project Takeaway

This project helped me understand how raw sales data can be converted into a dashboard that tells a business story.

Instead of looking at individual records, the dashboard makes it easier to identify patterns in **sales, cancellations, delivery performance, regional performance, and product sales**.

It also helped me practice using Excel not just for calculations, but for presenting data in a way that supports business decision-making.
