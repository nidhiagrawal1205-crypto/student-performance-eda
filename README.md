# 📊 Student Performance Analysis — EDA with Python

 *What really drives a student's success? Parental background? Preparation? Socioeconomics?*
*This project digs into the data to find out.*

![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-11557C?style=flat&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)



## 🧭 Project Overview

This project performs a full **Exploratory Data Analysis (EDA)** on a dataset of **1,000+ students** to uncover the factors that influence academic performance across math, reading, and writing.

The goal isn't just to visualize data — it's to extract **meaningful, real-world insights** from it.

---

## 📁 Repository Structure

student-performance-eda/
│
├── 📓 student_performance_analysis.ipynb   # Main analysis notebook
├── 📄 README.md                         
├── 📦 requirements.txt                     # Python dependencies
└── 🚫 .gitignore                           # Files excluded from version control




## 📌 Key Questions Explored

- 🎓 Does **parental education level** affect student scores?
- 🍱 Does **lunch type** (a socioeconomic proxy) correlate with performance?
- 📝 How much does completing a **test preparation course** matter?
- ⚧ Are there **gender-based differences** across subjects?
- 🏆 Which **demographic group** consistently outperforms others?

---

## 🔍 Methodology

| Phase | What Was Done |
|-------|--------------|
| **Data Cleaning** | Renamed columns, dropped unnamed index, checked for nulls & duplicates |
| **Feature Engineering** | Computed `avg_score' across math, reading, and writing |
| **Grouped Analysis** | Used '.groupby()' to compare performance across gender, race, lunch type, and test prep |
| **Visualization** | Bar charts and grouped comparisons to surface key patterns |

---

## 💡 Key Findings


📌 Finding 1 → Group E students have the highest average scores across all subjects
📌 Finding 2 → Students who completed test prep score significantly higher
📌 Finding 3 → Standard lunch correlates with better performance (socioeconomic signal)
📌 Finding 4 → Females outperform in reading & writing; males lead slightly in math
📌 Finding 5 → Within Group E, students with parents holding a master's degree top the charts


---

## 📊 Sample Visualizations

> Bar charts comparing average scores across race/ethnicity, lunch type, gender, and test prep completion are included in the notebook.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10| Core language |
| Pandas | Data manipulation & analysis |
| Matplotlib | Data visualization |
| Jupyter Notebook| Interactive analysis environment |

---

## 🚀 Getting Started

bash
# 1. Clone the repository
git clone https://github.com/nidhiagrawal1205-crypto/student-performance-eda.git

# 2. Navigate into the folder
cd student-performance-eda

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch the notebook
jupyter notebook student_performance_analysis.ipynb


---

## 📦 Requirements


pandas
matplotlib
jupyter


> Install all at once:  'pip install -r requirements.txt'



## 📂 Dataset

- **Source:** [Students Performance in Exams — Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Size:** 1,000 rows × 8 columns
- **Features:** Gender, Race/Ethnicity, Parental Education, Lunch Type, Test Prep Course, Math Score, Reading Score, Writing Score

---

## 🙋 About Me

I'm a data enthusiast passionate about finding stories hidden in structured data.
This project is part of my journey into data analytics — combining Python, statistical thinking, and visual storytelling.

📬 Connect with me on [LinkedIn](www.linkedin.com/in/nidhi-agrawal-8596292b1) | 
🐙 Explore more on [GitHub](https://github.com/nidhiagrawal1205-crypto)

---

## ⭐ If you found this useful

Give it a ⭐ — it helps others discover the project and motivates me to keep building!



*Made with 🐼 Pandas, 📊 Matplotlib, and a lot of curiosity.*
