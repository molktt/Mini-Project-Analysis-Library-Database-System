## 🧩 Project Overview
This project focuses on building a simple **library management database system** using **SQLite** integrated in **Python (Google Colab)**.  
The goal is to understand how to create, manipulate, and analyze relational data, including performing **SQL queries**, **data analysis**, and **visualization** using Pandas and Matplotlib/Seaborn.

The notebook demonstrates:
- Database creation and relationship modeling (Books, Members, Loans)
- Data insertion and querying using SQL commands
- Data exploration and visualization in Python

---

## 📌 Description
This project covers the complete workflow of a basic library information system:

1. **Database Design**
   - Create 3 related tables: `buku`, `anggota`, and `peminjaman`.
   - Apply primary & foreign key constraints.

2. **Data Management**
   - Insert book, member, and borrowing data.
   - Include active and returned loans (with `NULL` return dates).

3. **SQL Operations**
   - Perform `JOIN` queries to combine related tables.
   - Use `GROUP BY` and aggregation to summarize borrowing activities.

4. **Data Analysis & Visualization**
   - Load SQL query results into **Pandas DataFrame**.
   - Calculate loan duration and analyze borrowing patterns.
   - Visualize data distributions using **Matplotlib** and **Seaborn**.

---

## 🛠 Tools & Libraries Used
- **Python**
- **Google Colab / Jupyter Notebook**
- **SQLite3** – lightweight relational database
- **Pandas** – data manipulation & analysis
- **Matplotlib** – data visualization
- **Seaborn** – advanced visual analytics
- **NumPy** – numerical operations

---

## 📊 Key Insights
- 📅 Calculated borrowing durations (loan periods in days).
- 📚 Identified total books borrowed per member.
- 💡 Observed patterns in borrowing frequency and duration.
- 🎯 Visualized borrowing distribution and member activity using histograms and bar charts.

---

## 📁 Files Included
`Sistem_Basis_Data_Perpustakaan.ipynb` : Main Google Colab notebook with SQL queries, analysis, and visualizations 
`perpustakaan.db` : SQLite database file (auto-generated in Colab) 
`README.md` : Project documentation and overview

---

## 🚀 How to Run This Project
1. **Clone or download** this repository.
2. Open the `.ipynb` file in **Google Colab** or **Jupyter Notebook**.
3. Install dependencies if needed:
   ```bash
   pip install pandas matplotlib seaborn numpy
