# Student Performance Prediction System


## 📌 Project Overview
Traditional education systems often rely on intuition to identify struggling students. This project automates the process using Machine Learning to:
* **Predict** academic grades (A, B, C, D, F).
* **Identify** weak students early (Grades D and F).
* **Provide** data-driven insights for corrective teaching actions.

## 📊 Dataset Description
The project utilizes a dataset of **1,000,000 student records** featuring:
* `weekly_self_study_hours`: Independent study time.
* `attendance_percentage`: Class presence.
* `class_participation`: Interaction level (0-10).
* `grade`: Target variable (A-F).

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Tools:** Jupyter Notebook / VS Code

## 🚀 Methodology

### 1. Data Preprocessing
* Manual mapping of categorical grades to numeric values (A=0 to F=4).
* Feature selection focusing on behavioral metrics.
* Train-Test split (80/20).

### 2. Exploratory Data Analysis (EDA)
* Visualization of study hours vs. marks.
* Analysis of attendance impact on final grades.

### 3. Model Implementation
The project compares multiple ML algorithms to find the best balance between accuracy and interpretability:
1. **Logistic Regression** (~71% Accuracy)
2. **Decision Tree** (Best for Rule-based logic)
3. **Naive Bayes** (Fast probabilistic analysis)
4. **Support Vector Machine (SVM)** (High-dimensional boundaries)

## 📈 Key Outcomes
* **At-Risk Detection:** Automatically flags students with predicted grades D or F.
* **Trend Analysis:** Visual proof that attendance below 70% is a primary failure indicator.
* **Early Intervention:** Enables institutions to take preventive actions before final exams.

## 📂 Project Structure
```text
├── data/
│   └── student_performance.csv
└── student_performance.ipynb

├── README.md
