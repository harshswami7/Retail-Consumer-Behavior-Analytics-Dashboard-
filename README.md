# Retail Consumer Behavior Analytics Dashboard
## 📌 Project Overview
This project follows a professional corporate data analytics life cycle to analyze retail customer behavior. Using a dataset of thousands of transactions, I performed data cleaning in **Python**, executed advanced business queries in **SQL**, and developed a sleek, interactive dashboard in **Power BI**. The project concludes with a stakeholder presentation generated using AI and official documentation for a complete portfolio showcase.

## 🛠️ Tech Stack & Tools
* **Python (Pandas, NumPy):** Data cleaning, missing value imputation, and feature engineering.
* **PostgreSQL:** Advanced data analysis using CTEs and Window Functions.
* **Power BI:** KPI tracking and interactive data visualization.
* **Gamma AI:** Professional presentation deck generation.
* **GitHub:** Version control and project documentation.

---

## 📂 Data Analytics Life Cycle

### 1. Data Cleaning & Preparation (Python)
* **Imputation:** Handled missing review ratings by using the **median rating per category** (smarter than global mean) to avoid bias.
* **Standardization:** Converted all column headers to `snake_case` for seamless SQL integration.
* **Feature Engineering:** * Created `age_group` bins (Young Adult, Adult, Middle-Aged, Senior).
    * Mapped textual shopping frequencies (Weekly, Monthly) to numeric `days_between_purchases`.
* **Redundancy Check:** Identified and removed duplicate information columns to optimize the dataset.

### 2. Deep Dive Analysis (SQL)
Transformed business questions into optimized SQL queries:
* **Demographics:** Revenue split by Gender and Age Group.
* **High-Value Analysis:** Identifying customers using discounts who still spend more than the average purchase amount.
* **Advanced Ranking:** Used `ROW_NUMBER()` window functions to find the Top 3 most purchased items within every category.
* **Customer Segmentation:** Classified users as *New*, *Returning*, or *Loyal* based on previous purchase counts.
* **Loyalty Insights:** Analyzed whether repeat buyers are successfully converting into subscribers.

### 3. Interactive Dashboard (Power BI)
Built a high-performance dashboard featuring:
* **KPI Cards:** Total Customers, Average Purchase Value, and Average Review Rating.
* **Sales Trends:** Revenue by Category and Age Group.
* **Dynamic Filtering:** Integrated button-style slicers for Gender, Subscription Status, and Shipping Type.
* **Formatting:** Used rounded-corner design and accent bars for a modern, corporate UI/UX.

---

## 📊 Key Business Findings
* **Top Revenue Driver:** Young Adults are the most valuable demographic for the business.
* **Shipping Influence:** Express shipping correlates with higher average spend compared to standard delivery.
* **Subscription Gap:** A significant portion of "Loyal" customers (10+ purchases) have not yet subscribed, indicating a potential target for marketing campaigns.
* **Discount Reliance:** Certain categories (like Footwear) rely heavily on discounts to maintain sales volume.

---

## 🚀 How to Use
1.  **Python:** Run the `cleaning.ipynb` notebook to generate the `cleaned_data.csv`.
2.  **SQL:** Use the `queries.sql` file to create the database in PostgreSQL and run the analytical queries.
3.  **Power BI:** Open the `.pbix` file to explore the interactive dashboard.
4.  **Presentation:** Refer to the `presentation.pdf` for the summarized insights prepared for stakeholders.

---
