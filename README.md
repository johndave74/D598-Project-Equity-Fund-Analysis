# **D598 Project – Equity Fund Analysis**

## 📌 Overview

This project analyzes the performance of 150 U.S. companies in an equity fund, with the goal of supporting fund managers in rebalancing portfolio holdings. The dataset includes financial variables such as revenue, long-term debt, equity, and debt-to-equity ratio.

The project is divided into three tasks:

1. **Task 1 – Program Planning**

   * Flowchart showing program logic.
   * Pseudocode describing step-by-step operations.
   * Explanation of how the flowchart and pseudocode align.

2. **Task 2 – Coding**

   * Python program (Jupyter Notebook) to analyze the dataset.
   * Key functions:

     * Import dataset
     * Identify duplicates
     * Group data by state and compute descriptive statistics
     * Filter companies with negative debt-to-equity ratios
     * Create debt-to-income ratio and add it to the dataset
     * Export results to Excel files

3. **Task 3 – Presentation**

   * Explanation of code and workflow.
   * Four customized data visualizations with insights:

     1. Average Revenue by State
     2. Debt-to-Equity Ratio Distribution by State (Boxplot)
     3. Distribution of Debt-to-Income Ratios
     4. Average Debt-to-Income Ratio by State

---

## 📂 Repository Structure

```
D598-Project/
│
├── Task1/
│   ├── Task1_Flowchart.png
│
├── Task2-3/
│   ├── D598_Task2_Analysis.ipynb
│   ├── D598_Task2_Analysis.pdf
│   ├── Duplicates.xlsx
│   ├── State_Statistics.xlsx
│   ├── Negative_DE_Ratio.xlsx
│   └── Final_Data_with_DTI.xlsx
│
└── README.md
```

---

## 🚀 How to Run the Notebook

1. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn openpyxl
   ```
2. Place `D598 Data Set.xlsx` in the same folder as the notebook.
3. Open Jupyter Notebook and run:

   ```bash
   jupyter notebook D598_Task2_Analysis.ipynb
   ```
4. Outputs (Excel files + visualizations) will be generated automatically.

---

## 📊 Visualizations & Insights

* **Average Revenue by State** → Identifies high-performing states and potential concentration risk.
* **Debt-to-Equity Ratio Distribution by State** → Highlights leverage differences and financial risk variation.
* **Distribution of Debt-to-Income Ratios** → Shows overall debt burden across all companies.
* **Average Debt-to-Income Ratio by State** → Compares financial risk across states at a regional level.

---

## ✅ Deliverables

* Flowchart (PNG/Draw\.io)
* Pseudocode (DOCX/PDF)
* Jupyter Notebook with full analysis
* Excel output files
* Customized visualizations with explanations

---

## 👤 Author
**John David**
*Data Analyst*
## 👤 Owner
**Funmi**
MSDS Student – Western Governors University
