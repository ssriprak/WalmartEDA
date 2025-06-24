# 🛍️ Black Friday Purchase Behavior Analysis – Walmart

This project explores customer purchase behavior on Black Friday using real-world transactional data from Walmart. The goal is to understand how gender and other demographic factors influence spending patterns, and provide actionable business insights to Walmart's management.

---

## 📄 Project Objective

The Walmart Management Team seeks to determine:  
> **Do women spend more on Black Friday than men?**

Using this data, we aim to analyze purchase behavior across:
- Gender
- Age groups
- City categories
- Marital status
- Occupation and years in the current city

---

## 📦 Dataset Description

The dataset `walmart_data.csv` contains the following columns:

| Column Name                  | Description                                      |
|-----------------------------|--------------------------------------------------|
| `User_ID`                   | Unique identifier for each customer              |
| `Product_ID`                | Unique product identifier                        |
| `Gender`                    | Customer gender (`M` for Male, `F` for Female)   |
| `Age`                       | Age group (binned, e.g., `26-35`)                |
| `Occupation`                | Customer's occupation (masked values)            |
| `City_Category`             | Category of the city (`A`, `B`, or `C`)          |
| `Stay_In_Current_City_Years`| Years spent in current city (`0`, `1`, etc.)     |
| `Marital_Status`            | Marital status (`0` = Single, `1` = Married)     |
| `Product_Category`          | Product category (masked)                        |
| `Purchase`                  | Purchase amount in USD                           |

---

## 🧪 Assumptions

- Walmart’s customer base is 50% Male and 50% Female.
- All purchase data relates to Black Friday transactions.

---

## 🧰 Approach

### 🧹 Data Cleaning
- Handle null values
- Remove duplicates
- Convert data types
- Encode categorical columns (if needed)

### 📊 Data Exploration
- Compare average and total purchases by gender
- Segment analysis by age, city category, marital status
- Explore occupation and tenure in current city

### 📈 Visualizations
- Bar plots and box plots of purchase behavior
- Heatmaps for correlation
- Histograms for distribution checks
- Gender × Age and Gender × City Category interactions

---

## ✅ Outcome

The analysis will:
- Determine if gender affects Black Friday spending
- Identify demographic patterns in purchase behavior
- Suggest opportunities for customer segmentation and targeting

---
Part of StrataScratch Projects
