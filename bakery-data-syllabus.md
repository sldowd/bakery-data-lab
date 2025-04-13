# 🍞 Bakery Manager Data Science Mini Curriculum

**Student:** Sarah  
**Context:** Building on your bakery-manager CLI & database app, this curriculum layers on real-world data science skills using Python, pandas, and Jupyter. It mirrors your programming progress while deepening your analytics knowledge.

---

## 🧁 Overview
This 5-course progression will teach you how to:
- Load and explore data from your bakery-manager app
- Visualize trends in inventory and transactions
- Predict future needs and model simple forecasts
- Build presentable dashboards

You'll work in Jupyter notebooks using data from your SQLite database or Rust-exported CSVs.

---

## 🍽️ Course Menu

### 🥐 Course 1: Data Wrangling with pandas
**Goal:** Load, inspect, and clean bakery data

**Topics:**
- Reading SQLite or CSV into DataFrames
- `.head()`, `.info()`, `.describe()`
- Filtering, sorting, and grouping

**Exercise Ideas:**
- Load your `transactions` table and summarize by `transaction_type`
- Filter inventory to show low-stock items

---

### 🍰 Course 2: Visualization with matplotlib & seaborn
**Goal:** Understand and communicate patterns

**Topics:**
- Line plots for sales or ingredient use
- Bar/pie charts for revenue categories
- Styling and labeling

**Exercise Ideas:**
- Bar chart of ingredient usage
- Pie chart of expense categories by amount

---

### 🍞 Course 3: Time Series & Rolling Averages
**Goal:** Project ingredient depletion or profit trends

**Topics:**
- Converting to `datetime` and setting index
- Rolling window calculations
- Grouping by week/month

**Exercise Ideas:**
- Plot 7-day rolling revenue
- Predict when you’ll run out of eggs based on past usage

---

### 🥖 Course 4: Intro to Machine Learning with scikit-learn
**Goal:** Use simple predictive models

**Topics:**
- Linear regression with bakery features
- Binary classification: Low vs adequate stock
- Train/test splits and accuracy

**Exercise Ideas:**
- Predict total sales for a given day
- Classify inventory items that need restocking

---

### ☕ Course 5: Dashboards & Presentation
**Goal:** Build an interactive or printable summary of bakery operations

**Topics:**
- `streamlit` or `Jupyter` dashboards
- Export charts to images/PDF
- Display most-used ingredients and sales totals

**Exercise Ideas:**
- Dashboard with tabs for inventory, sales, and projections
- Print/PDF weekly bakery summary for team use

---

## 🧰 Toolchain
| Tool            | Purpose                       |
|-----------------|-------------------------------|
| pandas          | dataframes, grouping, analysis|
| matplotlib      | charts and visuals            |
| seaborn         | styled visuals                |
| scikit-learn    | simple machine learning       |
| streamlit       | dashboards (optional)         |
| sqlite3/sqlalchemy | load directly from CLI db |

---

## 🧑‍🍳 Suggestions for Organizing Files
You can either:

**Option A: Keep it separate (recommended to start)**
- Create a new repo or folder: `bakery-data-lab`
- Import data via SQLite or export CSV from your CLI

**Option B: Integrate later**
- Move your `.ipynb` notebooks into `/analysis` inside `bakery-manager`
- Use Python to connect directly to your CLI database (`sqlite3.connect()`)

---

## 🚀 Starter Kit Available
Ask for:
- Jupyter starter notebook (`transactions_analysis.ipynb`)
- Sample SQLite connector script
- Visualization templates

---



