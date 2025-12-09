
# **Customer Shopping Behavior Analysis 

## **📌 Overview**

This project analyzes customer shopping behavior using a structured workflow that includes Python, SQL, and Power BI. The goal is to understand spending patterns, top-performing products, customer segments, discount usage, and subscription behavior. The project also includes a written report and a presentation created using Gamma.

---

## **📊 Dataset**

* **Rows:** 3,900
* **Columns:** 18
* Includes demographic details, product information, purchase amounts, review ratings, shipping types, and shopping behavior metrics.
* Missing values were handled during preprocessing.

---

## **🛠 Tools & Technologies**

* **Python:** pandas, numpy, matplotlib, seaborn, SQLAlchemy
* **SQL Databases:** PostgreSQL / MySQL / SQL Server
* **Power BI:** for dashboards and interactive visuals
* **Gamma:** for creating project presentation
* **GitHub:** version control and documentation

---

## **🔍 Project Steps**

### **1. Data Loading**

* Imported the dataset into Python using pandas.
* Checked structure (`df.info()`) and summary statistics (`df.describe()`).

### **2. Exploratory Data Analysis (EDA)**

* Analyzed distributions, correlations, and category trends.
* Identified missing values, outliers, and potential inconsistencies.

### **3. Data Cleaning & Feature Engineering**

* Handled missing values (e.g., review ratings).
* Standardized column names.
* Engineered new fields such as **age groups** and **purchase frequency**.
* Removed redundant or low-value columns.

### **4. Database Integration**

* Loaded cleaned data into a SQL database (PostgreSQL/MySQL/SQL Server).
* Used SQL queries to analyze revenue, customer segments, product performance, discount patterns, and subscription behavior.

### **5. Dashboard Development (Power BI)**

Built an interactive Power BI dashboard showing:

* Total customers
* Average purchase amount
* Subscription breakdown
* Revenue by category
* Sales and revenue by age group
* Top products
* Interactive filters (Gender, Category, Shipping Type, etc.)

### **6. Report Creation**

* Prepared a detailed project report summarizing the findings and insights.

### **7. PPT Creation (Gamma)**

* Designed a clean, modern presentation summarizing objectives, methods, insights, visuals, and recommendations.

---

## **📈 Key Results & Insights**

* Identified top-rated and best-selling products.
* Analyzed subscription behavior vs. spending.
* Compared purchase patterns across age groups and genders.
* Evaluated impact of discounts and shipping types on revenue.
* Highlighted customer segments such as new, returning, and loyal shoppers.

---

## **▶ How to Run This Project**

### **1. Clone the repository**

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### **2. Install required Python packages**

```bash
pip install -r requirements.txt
```

### **3. Set up your database**

* Create a PostgreSQL/MySQL/SQL Server database.
* Update connection details in the Python script.
* Run the ETL script to load the cleaned data into SQL.

### **4. Run Python scripts**

```bash
python eda_and_cleaning.py
python load_to_sql.py
```

### **5. Open the Power BI file**

Load the `.pbix` file included in the repository to explore the dashboard.

### **6. View Report and Presentation**

* Open the PDF report for full documentation.
* Open the Gamma presentation link included in the repo.


