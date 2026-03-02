Student Performance Prediction

Overview

This project builds a machine learning model to predict student exam performance based on academic, demographic, and behavioral features.

The goal is to:
	•	Analyze which factors influence student performance
	•	Perform structured exploratory data analysis (EDA)
	•	Build regression models
	•	Compare model performance using quantitative metrics

This is a supervised regression problem where the target variable is the final exam score.

⸻

Dataset

The dataset includes features such as:
	•	Study time
	•	Attendance
	•	Parental education level
	•	Previous academic scores
	•	Lifestyle-related factors

Target variable:
	•	Final exam score

The dataset is stored inside the data/ directory.

⸻

Approach

The project follows this workflow:
	1.	Data cleaning and preprocessing
	2.	Exploratory Data Analysis (EDA)
	3.	Feature selection
	4.	Train-test split
	5.	Model training
	6.	Model comparison

⸻

Models Implemented

1. Linear Regression
	•	Baseline regression model
	•	Assumes linear relationship between features and target
	•	Easily interpretable coefficients

2. Random Forest Regressor
	•	Ensemble-based model
	•	Captures non-linear feature interactions
	•	Reduces overfitting through averaging

⸻

Evaluation Metrics

Models are evaluated using:
	•	R² Score — Measures how well the model explains variance
	•	Mean Absolute Error (MAE) — Measures average prediction error

Performance comparison determines which model generalizes better.

⸻

Project Structure

student-performance-ml/
│
├── data/
├── student_model.ipynb
├── requirements.txt
├── README.md
├── .gitignore

⸻

Installation & Setup

Clone repository:

git clone git@github.com:keerthilavu/student-performance-ml.git
cd student-performance-ml

Create virtual environment:

python3 -m venv venv
source venv/bin/activate

Install dependencies:

pip install -r requirements.txt

Run notebook:

jupyter notebook


⸻

Results

Random Forest achieved better R² score compared to Linear Regression, indicating that non-linear relationships significantly improve predictive performance.

(Exact metrics will be updated after full experimentation.)

⸻

Future Improvements
	•	Feature engineering
	•	Hyperparameter tuning
	•	Cross-validation
	•	Model deployment using Flask or FastAPI

⸻

Tech Stack
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn
	•	Scikit-learn

⸻

Author

Keerthi Lavu
GitHub: https://github.com/keerthilavu
