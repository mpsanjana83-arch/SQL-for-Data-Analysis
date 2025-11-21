# SQL-for-Data-Analysis
task3
# Task 3: SQL for Data Analysis

This project contains SQL queries used to analyze a simple e-commerce dataset.  
It follows the task requirements step-by-step and uses MySQL.


## 📌 Dataset Used

Three sample tables were created:

### **1. users**
| user_id | name |
|--------|------|

### **2. products**
| product_id | product_name | price |

### **3. orders**
| order_id | user_id | product_id | quantity |

These tables contain small sample data to make learning easy.

---

## 📌 Task Requirements Completed

### ✅ **(a) SELECT, WHERE, ORDER BY, GROUP BY**
Basic data retrieval and filtering queries.

### ✅ **(b) JOINS**
- INNER JOIN  
- LEFT JOIN  
- RIGHT JOIN  

Used to connect users, products, and orders.

### ✅ **(c) Subqueries**
Used to filter users based on total items purchased.

### ✅ **(d) Aggregate Functions**
- SUM()
- AVG()

Used to calculate total revenue and average revenue.

### ✅ **(e) Views**
Created a view named **order_summary** for displaying combined order information.

### ✅ **(f) Indexes**
Created an index on user_id to speed up queries.

---

## 📌 Files Included

- **task3.sql** – all SQL queries (table creation, insert, joins, subqueries, etc.)
- **task3_sql_solution.pdf** – full explanation of the task  
- **README.md** – this file

---

## 📌 How to Run

1. Open MySQL Workbench.
2. Create a new schema.
3. Open **task3.sql** file.
4. Run all queries.
5. View outputs and take screenshots if needed.

---

## 📌 Output Includes

- User list  
- Order filtering with WHERE  
- Sorted product prices  
- Total items per user  
- Order details using JOIN  
- Revenue calculations  
- View results  
- Indexed table optimization  

---

## 📌 Summary

This task helps understand:
- SQL data analysis  
- Query writing  
- Table relationships  
- Aggregations & joins  
- Creating views  
- Query optimization  

It is suitable for beginners and easy to run.


