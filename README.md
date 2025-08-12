
---
![statupexpansion](https://github.com/user-attachments/assets/9055cf0b-81a2-4f6f-9df7-87957e5fba0d)

```markdown
this is a great Dashboard by powerpi
# 📊 Data Analysis Capstone – Startup Expansion

This project presents a comprehensive data analysis of startup expansion across various cities and states. The dataset contains information about marketing spend, revenue, store location, and expansion status, which we explore and analyze to generate meaningful insights.

---

## 📁 Dataset

The dataset used in this project is stored in:
```
datasets/startup-expansion.xlsx
```

It includes the following key columns:
- `Store ID`
- `City`, `State`, `Sales Region`
- `Marketing Spend`
- `Revenue`
- `New Expansion` (New or Old expansion)

---

## 🔧 Tools & Libraries Used

- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** & **Seaborn** for visualization

---

## 🧠 Project Workflow

### 1. **Importing Libraries**
Standard Python data science libraries are imported to work with, visualize, and manipulate the data.

### 2. **Loading & Inspecting the Data**
We load the dataset and examine its structure using `.info()` and `.describe()` functions.

### 3. **Preprocessing**
- Count and inspect unique cities, states, and sales regions.
- Check for missing values and duplicates.
- Verify uniqueness of `Store ID`.

### 4. **Data Exploration & Analysis**
- Visualize store distribution by sales region.
- Identify top 10 revenue-generating states for both **new** and **old** expansions.
- Calculate:
  - **Profit** = Revenue - Marketing Spend
  - **ROMS (Return on Marketing Spend)** = Profit / Marketing Spend

### 5. **Exporting Cleaned Data**
The final cleaned and enriched dataset is saved as:
```
startups-expansion-modified.csv
```

---

## 📈 Sample Visuals & Insights

- Bar plots showing store count by region
- Top states contributing to revenue
- Calculated financial metrics like **Profit** and **ROMS**

---

## 💾 Output Files

- `startups-expansion-modified.csv`: The processed dataset with additional metrics.

---

## ✅ Requirements

Ensure you have the following installed:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

> `openpyxl` is required for reading `.xlsx` files with `pandas`.

---

## 🙌 Acknowledgments

Thanks to the data providers and the inspiration to analyze startup business expansions to generate smarter decisions using data-driven insights.

---

## 🚀 Happy Analyzing!
```

---

**Author**
--Mido khale
Store ID | City | State | Sales Region | New Expansion | Marketing Spend | Revenue | Profit | ROMS | ROMS%
1 | Peoria | Arizona | Region 2 | Old | 2601 | 48610 | 46009 | 1768.9 | 17.689
2 | Midland | Texas | Region 2 | Old | 2727 | 45689 | 42962 | 1575.43 | 15.7543
