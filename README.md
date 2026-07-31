# 🎓 Student Performance Prediction

A machine learning regression project that predicts a student's exam score based on factors like study hours, attendance, previous academic performance, and sleep habits.

## 📌 Project Overview
This project demonstrates a full regression ML pipeline — from data generation and EDA to model training, evaluation, and prediction on new data.

## 📊 Dataset
Since no single standard public dataset exists for this exact use case, a **synthetic dataset** of 500 student records is generated within the notebook, using realistic relationships between input features and exam scores plus random noise.

**Features used:**
- `study_hours` — Average daily study hours
- `attendance` — Class attendance percentage
- `previous_score` — Previous exam score
- `sleep_hours` — Average daily sleep hours
- `extra_activities` — Participation in extracurricular activities (0/1)

**Target:** `exam_score` (0–100)

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🔍 Workflow
1. Synthetic dataset generation
2. Exploratory Data Analysis (correlation heatmap, pairplots, score distribution)
3. Train-test split and feature scaling
4. Model training: Linear Regression, Random Forest Regressor
5. Model evaluation: RMSE, MAE, R² Score
6. Actual vs Predicted visualization
7. Feature importance analysis
8. Sample prediction for a new student

## 📈 Results
| Model | R² Score | RMSE |
|-------|----------|------|
| Linear Regression | ~0.85 | ~5.5 |
| Random Forest | ~0.87 | ~5.1 |

*(Actual results may vary slightly depending on random seed)*

## 🚀 How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run all cells sequentially
3. No file upload required — dataset is generated in-notebook

## 📁 Files
- `student_performance_prediction.ipynb` — Main notebook with full code

## 📌 Key Insight
Study hours and previous academic performance were the most influential factors in predicting exam scores, followed by attendance and sleep.

## 🧑‍💻 Author
Your Name

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
