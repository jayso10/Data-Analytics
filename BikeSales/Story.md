## 🚲 Bike Sales Data Analysis

This repository contains my end-to-end data analytics project on bike sales, designed to demonstrate skills in **SQL**, **data transformation**, and **Tableau dashboarding**.

---

### 📊 Project Overview

The goal of this project is to analyze bike sales data and uncover insights into customer behavior, product performance, and sales trends.

---

### 🧠 Approach

#### 1. 🧹 Data Preparation & Cleaning (MySQL)

* **Created all necessary tables** using `CREATE TABLE` and inserted data using `INSERT INTO`, as the original database source wasn’t available.
* **Normalized the structure** into separate dimension and fact tables (e.g., customers, products, orders).
* **Cleaned data** by:

  * Ensuring date formats were consistent
  * Handling null values  in the SQL inserts
  * Checking data consistency (e.g., foreign key relationships)
* **Joined the tables** using `INNER JOIN`  queries to create a final flat table `(`BikeStores.csv ) that combined customer, product, store, and order data.

#### 2. 📄 Export to CSV

* Exported the joined dataset into a `.csv` file for use in Tableau.
* Verified the data in Excel to ensure that columns, data types, and formats were suitable for visualization.

#### 3. 📊 Dashboard Creation (Tableau)

* Imported the CSV into Tableau Public.
* Designed a dashboard featuring:

  * **Sales by category and brand**
  * **Sales by location and store**
  * **Customer and sales rep performance**
  * **Monthly and yearly sales trends**
* Added interactivity via filters and tooltips for end-user exploration.

#### 4. 📈 Analysis Focus

* **Sales Trends**: Identified peak months and trends over time.
* **Top Products**: Highlighted high-performing categories and brands.
* **Regional Sales**: Compared performance across states and stores.
* **Customer Insights**: Highlighted Top Customers

---

### 🗂️ Repository Structure

```
.
├── BikeStores.sql        # SQL script to join all tables
├── BikeStores.csv        # Final cleaned, joined dataset used for Tableau
├── BikeStores sample databases # Drop existing tables
├── BikeStores sample databases #Create Schema and tables
├── BikeStores sample databases #Insert into tables
├── README.md             # Project documentation

```

---

### 🛠️ Tools Used

* **MySQL** – Data modeling, cleaning, joining
* **Tableau Public** – Dashboard creation
* **Excel** – Data inspection and CSV formatting

---

### 🔗 D[ashboard Lin](https://public.tableau.com/app/profile/justice.sosu/viz/BikeSales_17498547885450/BikeSalesDashboard)[k](https://public.tableau.com/app/profile/justice.sosu/viz/BikeSales_17498547885450/BikeSalesDashboard)

[👉 ](https://public.tableau.com/app/profile/justice.sosu/viz/BikeSales_17498547885450/BikeSalesDashboard)[View the Bike Sales Dashboard on Tableau Public](https://public.tableau.com/app/profile/justice.sosu/viz/BikeSales_17498547885450/BikeSalesDashboard)

---

### 📅 How to Use

1. Clone this repository.
2. Create tables and schema using the sample databases file
3. Run the `BikeStores.sql` file in a local SQL environment to rebuild the database.
4. Use the `BikeStores.csv` file for direct dashboarding or analysis in Excel or Tableau.

---

### ✅ Key Takeaways

* Practiced **manual data modeling** when a source database wasn’t available.
* Strengthened **SQL skills** for data cleaning and joining.
* Learned how to prepare datasets for BI tools like Tableau.
* Focused on **building user-friendly, insightful dashboards** for non-technical audiences.
