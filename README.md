📊 Employee Attrition Prediction (Classification Project)
📌 Project Overview

Employee attrition is a major challenge for organizations as it impacts productivity and increases hiring costs.
This project aims to predict whether an employee is likely to leave the company using machine learning classification techniques.

🎯 Objective
Analyze employee data to identify factors affecting attrition
Build classification models to predict employee turnover
Help HR teams take proactive decisions to retain employees
📂 Dataset
Source: IBM HR Analytics Employee Attrition Dataset
Records: ~1470 employees
Features include:
Age
Job Role
Monthly Income
Work Experience
Job Satisfaction
Overtime
Attrition (Target Variable)
⚙️ Technologies Used
Python 🐍
Pandas, NumPy
Matplotlib, Seaborn (Visualization)
Scikit-learn (ML Models)
XGBoost
🔍 Exploratory Data Analysis (EDA)
Checked missing values and data types
Analyzed class imbalance
Visualized:
Attrition distribution
Salary vs Attrition
Job Role impact
Overtime effect
🧹 Data Preprocessing
Label Encoding / One-Hot Encoding
Feature Scaling (StandardScaler)
Handling class imbalance (if applied)
Train-Test Split
🤖 Models Used
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Gradient Boosting
XGBoost
Support Vector Machine (SVM)
📈 Model Performance
Model	Accuracy
Logistic Regression	87%
KNN	82%
Decision Tree	73%
Random Forest	86%
Gradient Boosting	87.77%
XGBoost	87.41%
SVM	87.6%
🏆 Best Model

Gradient Boosting performed the best with 87.77% accuracy, followed closely by SVM and XGBoost.
It provides a good balance between bias and variance.

📊 Key Insights
Employees working overtime are more likely to leave
Lower salary employees show higher attrition
Job satisfaction plays a major role
Certain job roles have higher turnover rates
🚀 How to Run the Project
# Clone the repository
git clone https://github.com/your-username/employee-attrition.git

# Navigate to project folder
cd employee-attrition

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
📌 Future Improvements
Hyperparameter tuning
Deploy using Flask / Streamlit
Use Deep Learning models
Add real-time HR dashboard
📎 Conclusion

This project demonstrates how machine learning can be used to predict employee attrition and help organizations take preventive actions.
The model can assist HR departments in improving employee retention strategies.

👩‍💻 Author
Sanjana
Aspiring Data Analyst
