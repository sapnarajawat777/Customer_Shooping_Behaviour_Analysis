# 🛍️ Customer Shopping Behavior Analysis

An end-to-end Data Analytics project that analyzes **3,900 customer purchase records** to identify customer shopping patterns, spending behavior, product preferences, discount usage, subscription trends, and customer loyalty.

The project demonstrates the complete analytics pipeline, starting from data cleaning and preprocessing in Python, database integration using PostgreSQL, SQL-based business analysis, and interactive dashboard development in Power BI.

---

## 📌 Project Objective

The objective of this project is to transform raw customer shopping data into meaningful business insights by:

* Cleaning and preprocessing the raw dataset
* Handling missing and inconsistent data
* Performing exploratory data analysis using Python
* Loading cleaned data into PostgreSQL
* Performing SQL-based business analysis
* Analyzing customer segments and purchasing behavior
* Building an interactive Power BI dashboard
* Providing actionable business recommendations

---

## 📂 Dataset Information

**Dataset:** Customer Shopping Behavior Dataset

**Records:** 3,900

**Columns:** 18

### Dataset Contains:

#### 👤 Customer Information

* Customer ID
* Age
* Gender
* Location
* Subscription Status

#### 🛍️ Purchase Information

* Item Purchased
* Category
* Purchase Amount
* Season
* Size
* Color

#### 📊 Shopping Behavior

* Review Rating
* Shipping Type
* Discount Applied
* Promo Code Used
* Previous Purchases
* Payment Method
* Frequency of Purchases

---

# 🛠️ Project Workflow

## Step 1: Data Cleaning & Preprocessing (Python)

### Tools Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

### Tasks Performed

✔ Imported the dataset using Pandas

✔ Explored the dataset using:

```python
head()
info()
describe()
```

✔ Checked for missing values

✔ Handled missing review ratings using category-wise median imputation

✔ Standardized column names into `snake_case`

✔ Created an `age_group` feature

✔ Created a `purchase_frequency_days` feature

✔ Checked data consistency between discount and promotional code columns

✔ Removed redundant columns

✔ Checked duplicate records

✔ Performed exploratory data analysis

✔ Prepared the cleaned dataset for database analysis

### Skills Used

* Data Cleaning
* Data Preprocessing
* Missing Value Handling
* Feature Engineering
* Exploratory Data Analysis
* Data Transformation

---

# Step 2: Database Management (PostgreSQL)

### Tools Used

* PostgreSQL
* SQLAlchemy
* Python

### Tasks Performed

✔ Connected Python with PostgreSQL using SQLAlchemy

✔ Created a PostgreSQL database connection

✔ Uploaded the cleaned DataFrame into PostgreSQL

✔ Created the required database table

✔ Verified successful data insertion

✔ Prepared structured data for SQL-based analysis

### Skills Used

* Database Connectivity
* SQLAlchemy
* PostgreSQL
* Data Import
* Database Management

---

# Step 3: Business Analysis (SQL)

### Tools Used

* PostgreSQL
* SQL

The cleaned customer data was analyzed using SQL to answer important business questions.

### Business Queries Performed

✔ Revenue comparison by gender

✔ Identified high-spending customers who used discounts

✔ Found the top 5 products based on average customer ratings

✔ Compared average purchase amounts between Standard and Express shipping

✔ Compared subscribers and non-subscribers

✔ Identified products with high discount dependency

✔ Segmented customers into:

* New Customers
* Returning Customers
* Loyal Customers

✔ Found the top 3 products within each category

✔ Analyzed the relationship between repeat purchases and subscriptions

✔ Analyzed revenue contribution by age group

### SQL Concepts Used

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* Aggregate Functions
* CASE Statements
* Subqueries
* Common Table Expressions (CTEs)
* Window Functions

### Skills Used

* SQL Query Writing
* Business Problem Solving
* Customer Analytics
* Data Analysis
* Database Management

---

# Step 4: Data Visualization (Power BI)

### Tools Used

* Power BI
* PostgreSQL Connector
* DAX

An interactive Power BI dashboard was created to visualize key customer shopping insights and business performance indicators.

## 📊 Dashboard Analysis

### 👥 Customer Analysis

* Customer Demographics
* Customer Segmentation
* New, Returning, and Loyal Customers
* Revenue by Age Group
* Subscription Behavior

### 🛍️ Product Analysis

* Top Products by Rating
* Top Products by Category
* Product Purchase Performance
* Discount-Dependent Products

### 💰 Revenue Analysis

* Revenue by Gender
* Average Purchase Amount
* Total Revenue
* Subscriber vs. Non-Subscriber Spending

### 🚚 Shopping Behavior Analysis

* Shipping Type Comparison
* Discount Usage
* Payment Method Analysis
* Purchase Frequency
* Repeat Purchase Behavior

### Skills Used

* Power BI
* DAX
* Data Modeling
* Interactive Dashboard Design
* Data Visualization
* Business Intelligence

---

# 💡 Key Business Insights

The analysis helped identify:

* Customer spending patterns across different demographics
* Differences in purchasing behavior between subscribers and non-subscribers
* High-value customers who use discounts
* Products with strong customer ratings
* Products that are highly dependent on discounts
* Customer loyalty patterns based on previous purchases
* Top-performing products within each category
* Relationship between repeat purchases and subscription behavior
* Revenue contribution across different age groups
* Shipping preferences and their relationship with purchase value

---

# 📈 Business Recommendations

### 1. 🚀 Increase Subscription Adoption

Promote exclusive benefits and offers to increase subscription adoption and improve customer retention.

### 2. 🎁 Strengthen Customer Loyalty Programs

Reward repeat customers and encourage Returning Customers to move into the Loyal Customer segment.

### 3. 💰 Optimize Discount Strategies

Analyze discount-dependent products carefully to increase sales while maintaining healthy profit margins.

### 4. ⭐ Promote Top-Rated Products

Use highly rated and best-selling products in marketing campaigns and promotional strategies.

### 5. 🎯 Target High-Revenue Customer Segments

Focus marketing campaigns on age groups and customer segments that contribute higher revenue.

---

# 💻 Technologies Used

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Data Cleaning & Analysis  |
| Pandas           | Data Manipulation         |
| NumPy            | Data Processing           |
| Matplotlib       | Data Visualization        |
| Seaborn          | Exploratory Data Analysis |
| SQLAlchemy       | Database Connection       |
| PostgreSQL       | Database Management       |
| SQL              | Business Analysis         |
| Power BI         | Dashboard & Visualization |
| DAX              | Dashboard Calculations    |
| Jupyter Notebook | Development Environment   |
| Git & GitHub     | Version Control           |

---

# 📁 Project Structure

```text
Customer_Shopping_Behavior_Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Jupyter_Notebook/
│   └── customer_shopping_behavior_analysis.ipynb
│
├── SQL/
│   └── customer_shopping_behavior_analysis.sql
│
├── PowerBI/
│   └── customer_shopping_behavior_dashboard.pbix
│
├── Report/
│   └── Customer Shopping Behavior Analysis.pdf
│
├── Presentation/
│   └── Customer Shopping Behavior Analysis.pptx
│
└── README.md
```

---

# 🎯 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Python
* Pandas
* NumPy
* SQL
* PostgreSQL
* SQLAlchemy
* Power BI
* DAX
* Data Visualization
* Business Intelligence
* Customer Analytics
* Business Analytics
* Dashboard Design
* Data-Driven Decision Making

---

# 🚀 Future Improvements

* Build a machine learning model to predict customer purchase behavior
* Develop a customer churn prediction model
* Predict customer lifetime value
* Create a recommendation system for products
* Build automated data pipelines
* Add real-time dashboard updates
* Deploy the Power BI dashboard using Power BI Service
* Add advanced customer segmentation using RFM Analysis

---

# 👩‍💻 Author

**Sapna Rajawat**

BCA Student | Aspiring Data Analyst

🔗 GitHub: [sapnarajawat777](https://github.com/sapnarajawat777)

🔗 LinkedIn: [Sapna Rajawat](https://www.linkedin.com/in/sapna-rajawat-62145432)

---

⭐ If you found this project useful, don't forget to star the repository!
