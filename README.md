# 🛒 Zepto Sales Data SQL Project

This SQL project is based on real-world retail sales data, inspired by Zepto's grocery and e-commerce model. The dataset (`zepto_v1.csv`) includes product-level information such as pricing, discounting, stock availability, and more.

## 📁 Dataset Overview

The dataset contains the following columns:

* **sku\_id**: Unique product identifier
* **category**: Product category (e.g., dairy, snacks, etc.)
* **name**: Product name
* **mrp**: Maximum Retail Price of the product
* **discountpercent**: Discount offered (in %)
* **availableQuantity**: Total units currently in stock
* **discountedsellingprice**: Final price after discount
* **weightingms**: Product weight in grams
* **outofstock**: Boolean flag indicating stock status
* **qunatity**: Quantity per unit

⚠️ Note: The original dataset had a BOM (Byte Order Mark) character in the column `sku_id`, which was cleaned during preprocessing.

---

## 🎯 Project Goals

* Practice and demonstrate SQL skills using real-world-style data
* Perform exploratory data analysis using SQL
* Solve business-related problems like:

  * Identifying high-discount products
  * Finding categories with frequent out-of-stock issues
  * Calculating total revenue potential
  * Analyzing pricing strategies

---

## 🧰 Tools Used

* **MySQL / PostgreSQL** (compatible SQL dialect)
* SQL editor: MySQL Workbench 
* Data cleaning using CSV tools and SQL scripts

---

## ✅ Key Insights Generated

* Adjusted MRP and Discounted Selling Price (divided by 100) to match real-world values
* Filtered products with unusually high discounts
* Listed top categories with most out-of-stock items
* Calculated potential revenue loss due to out-of-stock items
* Analyzed product pricing and category trends

---

## 📌 How you can use this file and data by yourself if you want i would advice you to try one time 

1. Load the `zepto_v1.csv` into your SQL database.
2. Clean the data if needed (e.g., fix BOM issues in headers).
3. Run the SQL queries to perform analysis or solve business problems.
4. Optionally, visualize the results using Power BI or Tableau.

---

Let me know if you want to add your specific SQL queries, create a `.sql` file of solved problems, or generate charts from the results.
