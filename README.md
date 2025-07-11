#  UPI Transaction Analysis Dashboard – Power BI

This project visualizes UPI (Unified Payments Interface) transaction data for the year 2024, helping uncover key insights across demographic segments, merchant activity, and transaction types using an interactive Power BI dashboard.

---

##  Problem Statement

UPI has become a dominant digital payment method in India, but understanding **how different user segments use it** — such as by **gender, city, merchant, or age group** — is complex when dealing with large volumes of raw data.

>  **Goal:** To build an interactive dashboard that simplifies 20,000+ rows of UPI transaction data into **insightful, filterable visuals** for exploration by city, bank, device type, age group, and more.

---

## Tools & Techniques Used

- **Power BI Desktop**
  - **Power Query Editor** – for data cleaning and shaping
  - **DAX** – for calculated columns and measures
  - **Bookmarks** – for visual toggles
  - **Slicers** – synced across pages for dynamic filtering
- Excel/CSV for initial data preparation
- Custom visualizations: **line chart, column chart, matrix**

---

## 📊 Dashboard Overview

The dashboard consists of **two interactive pages**:

###  Page 1 – Monthly Trends & Visual Toggles

- **Toggle between Line & Column Charts**
  - Compare **Amount** vs. **Remaining Balance**
  - Switch views using **Bookmarks**
- Filters for:
  - Bank sent/received, City, Device type, Gender, Age Group, Merchant, Payment method, Purpose, Transaction type

| View  | Screenshot |
|-------|------------|
| 📈 Line Chart – Amount | ![Line Chart](screenshots/overview.png) |
| 📊 Column Chart – Amount | ![Column Chart](screenshots/column.png) |
| 📈 Line Chart – Balance | ![Line Chart – Balance](screenshots/line_balance.png) |
| 📊 Column Chart – Balance | ![Column Chart – Balance](screenshots/column_balance.png) |

---

###  Page 2 – Drilldown by Merchant, Demographics, and City

- Focused on a filtered scenario:
  - Example: **Merchant = IRCTC**, **Gender = Female**, **Age Group = A3**
- Chart automatically updates to show specific trends

![Filtered Merchant View](screenshots/merchant_irctc_female.png)

---

###  Page 3 – City-Wise Matrix Breakdown

- Shows **Amount** and **Remaining Balance** by city and currency (e.g., USD, GBP)
- Fully interactive: updates based on filters applied

| View | Screenshot |
|------|------------|
| Matrix (normal) | ![Matrix – City-Wise](screenshots/city_matrix.png) |
| Matrix (filtered) | ![Matrix – Filtered](screenshots/city_matrix_filtered.png) |

---

## 📁 Files Included

- `upi_dashboard.pbix` → Power BI file
- `upi_transactions_dataset.csv` → Dataset (20,000+ rows, 20+ columns)
- `screenshots/` → Contains all dashboard images
- `README.md` → This project overview

---

##  Key Interactivity Features

- ✅ Slicers across multiple dimensions
- ✅ Bookmarks for toggling charts
- ✅ DAX measures for dynamic KPIs
- ✅ Matrix visuals with multiple currencies
- ✅ Filter syncing across all pages

---

## 📈 Insights Gained

- UPI activity shows **seasonal spikes** (e.g., in May & October)
- Merchants like **IRCTC** are highly active among specific segments
- City-wise distributions highlight regional payment behavior differences
- Filters allow narrowing data to **very specific audience segments**

---

## 🚀 Future Improvements

- Add **map visual** for geographic analysis
- Include **transaction volume % change** month-over-month
- Integrate **machine learning forecast** on transaction volume
- Add a **mobile-optimized layout**
- Deploy via **Power BI Service** with refresh capabilities

---

##  About Me

I'm a 3rd-year Computer Science student exploring the field of **data analytics** with a passion for storytelling through visuals. This project helped me strengthen skills in **Power BI, DAX, bookmarks, and dashboard design**.

📬 Connect with me on [LinkedIn](https://www.linkedin.com/in/ikanakagarwal)

