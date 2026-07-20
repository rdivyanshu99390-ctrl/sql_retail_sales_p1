# 🛍️ SQL Retail Sales Analysis

## 📌 Project Overview

**SQL Retail Sales Analysis** is a PostgreSQL project that demonstrates how SQL can be used to analyze retail sales data and extract meaningful business insights. The project covers the complete workflow—from database creation and data cleaning to exploratory data analysis and solving real-world business questions using SQL.
---

## 🎯 Objectives

* Design and create a retail sales database.
* Import and manage transactional sales data.
* Perform data cleaning by identifying and removing incomplete records.
* Explore the dataset using SQL.
* Solve business problems with SQL queries.
* Generate insights to support data-driven decision-making.

---

## 🗂️ Database Schema

The project uses a single table named **`retail_sales`**.

| Column          | Data Type | Description              |
| --------------- | --------- | ------------------------ |
| transactions_id | INT       | Unique transaction ID    |
| sale_date       | DATE      | Date of sale             |
| sale_time       | TIME      | Time of sale             |
| customer_id     | INT       | Customer identifier      |
| gender          | VARCHAR   | Customer gender          |
| age             | INT       | Customer age             |
| category        | VARCHAR   | Product category         |
| quantity        | INT       | Quantity purchased       |
| price_per_unit  | FLOAT     | Price per unit           |
| cogs            | FLOAT     | Cost of Goods Sold       |
| total_sale      | FLOAT     | Total transaction amount |

---

## 🛠️ Technologies Used

* PostgreSQL
* SQL
* pgAdmin 4

---

## 📚 SQL Concepts Covered

* Database Creation
* Table Creation
* Data Cleaning
* Data Exploration
* Filtering Data
* Aggregate Functions
* GROUP BY
* ORDER BY
* DISTINCT
* Date & Time Functions
* CASE Statements
* Common Table Expressions (CTEs)
* Window Functions (`RANK()`)
* Business Analytics

---

## 🧹 Data Cleaning

The project includes:

* Detecting NULL values
* Removing incomplete records
* Validating transaction data
* Preparing the dataset for analysis

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

* Total number of sales
* Total unique customers
* Product categories available
* Dataset validation

---

## 💼 Business Problems Solved

### 1. Retrieve all sales made on a specific date.

### 2. Find Clothing transactions with quantity greater than or equal to 4 during November 2022.

### 3. Calculate total sales and total orders for each product category.

### 4. Find the average age of customers purchasing Beauty products.

### 5. Retrieve transactions where total sales exceeded ₹1000.

### 6. Count transactions by gender and product category.

### 7. Identify the best-selling month in each year using Window Functions.

### 8. Find the Top 5 customers based on total sales.

### 9. Count unique customers for every product category.

### 10. Categorize sales into Morning, Afternoon, and Evening shifts and count total orders.

---

## 📈 Key Insights

* Category-wise revenue analysis
* Customer purchasing behavior
* Monthly sales trends
* High-value customers
* Gender-wise purchasing patterns
* Shift-wise sales distribution

---

## 📁 Project Structure

```text
sql_retail_sales_p1/
│
├── retail_sales.sql      # Database creation & analysis queries
├── README.md             # Project documentation
```

---

## 🚀 How to Run the Project

1. Install PostgreSQL and pgAdmin 4.
2. Create a new database.
3. Execute the SQL script.
4. Import the retail sales dataset.
5. Run the analysis queries.
6. Explore the generated business insights.

---

## 🎓 Learning Outcomes

By completing this project, I learned how to:

* Design relational databases
* Write efficient SQL queries
* Clean and validate datasets
* Perform business-oriented data analysis
* Use Aggregate Functions, CTEs, and Window Functions
* Generate actionable insights from transactional data

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

Feel free to fork this repository and submit a pull request.

---

## ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub.

---

## 👨‍💻 Author

**Divyanshu Raj**

* 🎓 B.A. Programme (Major: Computer Applications)
* 💻 Aspiring Backend Developer
* 🚀 Passionate about SQL, PostgreSQL, Node.js, and Data Analytics

---

**Thank you for visiting this repository! Happy Coding! 🚀**
