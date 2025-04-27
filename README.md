"""
# Student Performance Factors - Regression and Classification Models

This project analyzes the StudentPerformanceFactors.csv dataset from Kaggle.  
It focuses on building regression and classification models based on student-related factors.

---

## 📂 Project Structure
```
StudentPerformanceFactors/
│
├── regression model/
│   ├── linear_regression_model.joblib
│   ├── random_forest_model.joblib
│   └── xgboost_model.joblib
│
├── classification_model/
│   ├── logistic_regression_model.pkl
│   └── random_forest_model.pkl
│
├── StudentPerformanceFactors.ipynb
├── StudentPerformanceFactors_02.ipynb
├── cleaned_student_performance.csv
├── StudentPerformanceFactors.csv
└── README.md
```
---

## 🗂️ Dataset Information

**Original Dataset:**  
- StudentPerformanceFactors.csv (Kaggle)

**Columns:**
- Hours_Studied
- Attendance
- Parental_Involvement
- Access_to_Resources
- Extracurricular_Activities
- Sleep_Hours
- Previous_Scores
- Motivation_Level
- Internet_Access
- Tutoring_Sessions
- Family_Income
- Teacher_Quality
- School_Type
- Peer_Influence
- Physical_Activity
- Learning_Disabilities
- Parental_Education_Level
- Distance_from_Home
- Gender
- Exam_Score

---

## 🏆 Model Performance

| Model | Metric | Score |
| :--- | :--- | :--- |
| Linear Regression | R² Score | 0.7821 |
| Random Forest Regressor | R² Score | 0.6511 |
| XGBoost Regressor | R² Score | 0.7382 |
| Logistic Regression | Accuracy | 95.53% |
| Random Forest Classifier | Accuracy | 81.59% |

---

## 🔥 How to Use

- Open `StudentPerformanceFactors.ipynb` to run regression tasks.
- Open `StudentPerformanceFactors_02.ipynb` to run classification tasks.
- Trained models are saved separately inside the `regression model/` and `classification_model/` folders.
- The cleaned dataset is saved as `cleaned_student_performance.csv`.

---

## 🧑‍💻 Author

- **Name:** [Your Name Here]
- **GitHub:** [Your GitHub Username]

---
