# City_Library_Datat-analysis
Exploratory data analysis of City Library borrowing data using Python, Pandas, and Matplotlib.
# 📚 Library Data Analysis

## 📌 Overview

This project analyzes **City Library** data to understand borrowing behavior and identify patterns that can support better library management decisions.

The project focuses on borrowing activity, popular books and authors, active members, and borrowing patterns across different grades and genres.

---

## 🎯 Business Problem

How can City Library use its member and checkout data to:

* Understand borrowing behavior
* Identify popular books and authors
* Identify the most active readers
* Understand borrowing patterns across grades and genres
* Support better library management decisions

---

## ❓ Key Questions

The analysis answers the following questions:

1. How does borrowing activity change over time?
2. Which books and authors are the most popular?
3. Who are the most active library members?
4. How does borrowing vary across grades?
5. Which genres are most borrowed?

---

## 🗂️ Dataset

The dataset contains information about **members, checkouts, and books**.

### Main Information

* **Members:** Member ID, name, grade, neighborhood, membership status, join date
* **Checkouts:** Checkout ID, checkout date, return date
* **Books:** Book ID, title, author, genre, pages, publication year, publisher

The tables were combined to create a dataset suitable for analysis.

---

## 🧹 Data Preparation

Before performing the analysis, the data was prepared through several steps:

* Checked missing values
* Checked duplicated records
* Converted columns to appropriate data types
* Converted date columns to `datetime`
* Standardized text values
* Checked data inconsistencies
* Investigated date-related inconsistencies
* Reviewed the results of merging the datasets

Some data inconsistencies were identified but could not be reliably corrected due to insufficient information in the original data.

---

## 📊 Analysis & Visualization

The project uses **Exploratory Data Analysis (EDA)** and data visualization to identify important borrowing patterns.

The analysis includes:

* Borrowing activity over time
* Most borrowed books
* Most popular authors
* Most active members
* Borrowing by grade
* Borrowing by genre

Detailed analysis, visualizations, and findings are available in the **Jupyter Notebook** and **Project Report**.

---

## 🛠️ Tools & Technologies

* 🐍 Python
* 🐼 Pandas
* 📊 Matplotlib
* 📓 Jupyter Notebook

---

## 📁 Project Structure

```text
Library-Data-Analysis/
│
├── data/
│   └── library_data.csv
│
├── Library_data_analysis.ipynb
│
├── report/
│   └── Library_Data_Analysis_Report.pdf
│
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/USERNAME/Library-Data-Analysis.git
```

### 2. Install the required libraries

```bash
pip install pandas matplotlib jupyter
```

### 3. Open the notebook

Open:

```text
Library_data_analysis.ipynb
```

using Jupyter Notebook or VS Code.

### 4. Run the notebook

Run the cells from top to bottom to reproduce the analysis.

---

## 📄 Project Deliverables

* 📓 **Jupyter Notebook** — Data cleaning, exploration, analysis, and visualization
* 📑 **Project Report** — Summary of the analysis and key findings

---

## 👩‍💻 Author

**Malak Makld**

Artificial Intelligence Student
Mansoura University
