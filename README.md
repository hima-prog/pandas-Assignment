# Pandas for AI/ML – Technical Assessment

This repository contains my Pandas assignment completed as part of my AI/ML learning journey.

The assignment focuses on using **Pandas and NumPy** for data manipulation, analysis, debugging, preprocessing, and data cleaning.

## 📌 Assignment Overview

The assignment is divided into four sections:

- **Section A – Output Prediction**
- **Section B – Code Correction**
- **Section C – Edge Cases**
- **Section D – Scenario-Based Questions**

---

## 📂 Repository Contents

- `Hima_Pandas.ipynb` – Complete Jupyter Notebook containing the assignment
- `student_assessment_dirty.csv` – Dataset used for the data-cleaning task
- `README.md` – Repository documentation

---

## 📝 What I Did in Each Section

### 🔹 Section A – Output Prediction

In this section, I worked with given Pandas and NumPy code snippets and predicted their outputs.

I covered:

- NumPy arrays and Pandas Series
- Vectorized operations
- Boolean filtering
- Descriptive statistics
- Group-wise analysis using `groupby()`
- Positive correlation
- Negative correlation

I also explained the concepts behind the outputs, such as how filtering works, how group-wise averages are calculated, and how correlation represents relationships between variables.

---

### 🔹 Section B – Code Correction

In this section, I identified errors or incorrect implementations in the given Pandas code and corrected them.

I worked on:

- Reading CSV files correctly
- Sorting data to find the highest salaries
- Handling missing values using `fillna()`
- Calculating correlation between columns

For each question, I identified the issue, provided the corrected code, and explained what was changed.

---

### 🔹 Section C – Edge Cases

In this section, I worked with situations where Pandas or NumPy operations can produce unexpected results or require additional handling.

I covered:

- NumPy broadcasting
- Handling CSV files with quoted values
- Missing values
- Different date formats
- Numeric conversion
- Outlier analysis
- Mean vs. median
- Identifying invalid values

I also considered how unusual or missing data can affect the results and how to handle these cases appropriately.

---

### 🔹 Section D – Scenario-Based Data Cleaning

In this section, I worked with a real-world style student assessment dataset containing different data-quality issues.

The dataset includes:

- Missing marks
- Duplicate student records
- Inconsistent department names such as `IT`, `it`, and `I.T.`
- Text values such as `88 marks`
- `Absent` and `NA` values
- Marks outside the valid `0–100` range

I performed the following cleaning steps:

1. Loaded and inspected the CSV dataset.
2. Checked the dataset using `head()`, `info()`, and `isnull().sum()`.
3. Standardized department names.
4. Identified and removed duplicate records.
5. Converted the Marks column into a numeric format.
6. Handled values such as `Absent`, `NA`, blank values, and `88 marks`.
7. Investigated missing marks and distinguished between absent students and marks that were not entered.
8. Identified marks outside the valid range of `0–100`.
9. Displayed the cleaned dataset.
10. Reported the number of records removed, missing marks remaining, and invalid marks identified.

---

## 🧠 Key Concepts Practiced

Through this assignment, I practiced:

- Pandas Series and DataFrames
- NumPy arrays
- Vectorized operations
- Boolean filtering
- Sorting and grouping
- Descriptive statistics
- Correlation analysis
- Missing value handling
- Data type conversion
- CSV data handling
- Duplicate detection
- Data cleaning
- Outlier analysis
- Data validation
- NumPy broadcasting

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 🎯 Learning Outcome

This assignment helped me understand how Pandas and NumPy can be used to work with structured and messy datasets.

I gained practical experience in **data manipulation, data analysis, debugging, preprocessing, and data cleaning**, which are important steps in AI/ML workflows.

---

## ▶️ How to Run

1. Clone or download this repository.
2. Open `Hima_Pandas.ipynb` in Jupyter Notebook or JupyterLab.
3. Keep `student_assessment_dirty.csv` in the same folder as the notebook.
4. Run the notebook cells from top to bottom.
5. Check the outputs for each section.

---

## 👩‍💻 Author

**Hima Harshitha Janjanam**

**B.Tech – AI and ML**

---

⭐ This repository represents my practical learning and work with **Pandas and NumPy for AI/ML data manipulation, analysis, and preprocessing**.
