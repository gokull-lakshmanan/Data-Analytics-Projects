# E-Commerce SQL Analysis

## 📌 Project Overview
This project analyzes e-commerce data using SQL to extract meaningful insights. The dataset contains customer, order, payment, and delivery information, allowing us to explore various trends and patterns in online shopping behavior in Brazil.

## 📂 Repository Structure
```
├── Target-Brazil-Ecommerce(SQL)/
│   ├── documentation/
│   │   ├── .gitkeep
│   │   ├── TARGET_SQL_DOCUMENT.pdf
│   ├── sql/
│   │   ├── .gitkeep
│   │   ├── queries.sql
│   ├── README.md
```

## 🗂️ Dataset & Tables Used
The analysis is conducted on the `Business_Case_Target_SQL` database, which contains the following CSV files:

- **customers.csv**: Customer demographic details
- **sellers.csv**: Seller demographic details
- **order_items.csv**: Order and pricing details
- **geolocation.csv**: Geographical mapping of customer and seller locations
- **payments.csv**: Payment method and transaction amounts
- **reviews.csv**: Customer reviews and feedback
- **orders.csv**: Order timestamps and delivery information
- **products.csv**: Product category and specification details

## 📊 Key Analyses & Findings
### 1️⃣ Exploratory Data Analysis
- Checked data types for all columns in the `customers` table.
- Identified the order placement time range (from September 2016 to October 2018).
- Counted the number of unique cities (4,119) and states (27) from which orders were placed.

### 2️⃣ Trend & Seasonal Analysis
- **Yearly Order Trends:** Orders increased significantly from 2016 (329 orders) to 2018 (54,011 orders), indicating a growing trend.
- **Seasonality:** Peaks in November-December due to holiday shopping and a drop in September.
- **Time of Day Analysis:** Most orders were placed in the afternoon (13-18 hrs), with 38,135 orders.

### 3️⃣ Regional Analysis
- **Monthly Orders by State:** Analyzed order trends across different states.
- **Customer Distribution:** Identified the number of customers per state.

### 4️⃣ Economic Impact Analysis
- **Order Cost Growth:** A 136.98% increase in payment value from 2017 to 2018 (Jan-Aug).
- **Total & Average Order Price by State:** Summarized pricing insights per region.
- **Total & Average Freight Cost by State:** Evaluated logistics expenses.

### 5️⃣ Logistics & Delivery Insights
- **Delivery Time Analysis:** Calculated actual vs. estimated delivery delays.
- **Freight Costs:** Identified states with the highest and lowest shipping costs.
- **Delivery Speed Ranking:** Ranked states by fastest delivery performance.

### 6️⃣ Payment Behavior Analysis
- **Payment Method Trends:** Monthly breakdown of orders by payment type.
- **Installment-based Purchases:** Count of orders based on payment installments.

## 🔧 Technologies Used
- **SQL** for querying and analysis
- **Google BigQuery**
