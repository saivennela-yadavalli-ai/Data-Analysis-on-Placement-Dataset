# 📊 Data Analysis on Placement Dataset

## 📌 Project Overview
This project analyses a Placement dataset to extract insights into student placement outcomes and salary distribution.  
The goal is to apply **data preprocessing, cleaning, and visualisation techniques** to answer business-oriented questions.

---

## 📂 Dataset
- **File Name:** Placement.csv  
- **Description:** The dataset contains student academic records, placement status, and salary details.  
- **Key Columns:**
  - `sl_no` – Serial number (removed during preprocessing)
  - `gender` – Gender of the student
  - `ssc_p` – Secondary Education percentage
  - `hsc_p` – Higher Secondary Education percentage
  - `degree_p` – Degree percentage
  - `status` – Placement status (Placed / Not Placed)
  - `salary` – Salary offered (NaN for Not Placed students)

---

## ⚙️ Steps Performed
1. **Importing Libraries**
   - Used `pandas`, `numpy`, `matplotlib`, and `seaborn` for analysis and visualisation.

2. **Loading Dataset**
   - Read the dataset into a pandas DataFrame.

3. **Handling Missing Values**
   - Salary column contained NaN values for "Not Placed" students.  
   - Replaced with `0` to retain dataset meaning (instead of mean/median).

4. **Data Cleaning**
   - Dropped irrelevant column `sl_no`.

5. **Exploratory Data Analysis (EDA)**
   - Checked distribution of placed vs not placed students.
   - Analysed salary distribution.
   - Compared placements across gender and degree specialisations.
   - Visualized data using histograms, bar charts, and scatter plots.

---

## 📊 Insights
- Not Placed students correctly represented with `salary = 0`.
- Placement chances strongly depend on degree percentage and specialisation.
- Higher SSC/HSC percentages correlate with better placement chances.
- Salary distribution is positively skewed, with most students in lower salary ranges and a few receiving high packages.

---

## 🚀 Tools & Libraries
- Python 3.x
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🏁 Conclusion
This project demonstrates:
- How to handle missing values logically.
- The importance of preprocessing before analysis.
- Insights into student placement patterns through visualisation.

---

## 📜 Author
- Sai Vennela Yadavalli
---

## ✨ Quote
*"Data is a precious thing and will last longer than the systems themselves."* – Tim Berners-Lee
