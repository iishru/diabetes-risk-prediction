# 🩺 Diabetes Risk Prediction System

An interactive machine learning tool that predicts diabetes risk based on patient medical data.

---

## 🚀 Project Overview

This project uses a **Random Forest classifier** trained on the **Pima Indians Diabetes Dataset** to assess a patient's risk of diabetes. The system provides **risk scores**, **prediction probabilities**, and explains which factors are contributing most to the prediction.

---

## 🔍 Features

- Data preprocessing to handle missing values
- Intuitive risk scoring system combining multiple factors
- Interactive patient assessment with detailed explanations
- Visualizations of feature distributions and importance
- Three-level risk classification: **Low**, **Borderline**, **High**

---

## ⚙️ How It Works

1. Loads and preprocesses the **Pima Indians Diabetes Dataset**
2. Creates data visualizations to understand patterns in the dataset
3. Trains a **Random Forest model** to recognize patterns associated with diabetes
4. Provides an interactive interface to enter patient data
5. Calculates a weighted **risk score** and model **prediction**
6. Explains which factors are most influential for each prediction

---

## 🖥️ Sample Output

🩺 Diabetes Risk Prediction System 🩺 Enter patient details to predict diabetes risk (Enter 'q' to quit)

Enter Pregnancies (or press Enter for median value): 2 Enter Glucose (or press Enter for median value): 130 Enter BloodPressure (or press Enter for median value): 80 Enter SkinThickness (or press Enter for median value): 25 Enter Insulin (or press Enter for median value): 100 Enter BMI (or press Enter for median value): 32 Enter DiabetesPedigreeFunction (or press Enter for median value): 0.5 Enter Age (or press Enter for median value): 45

📊 Results 📊 Risk Score: 1.25 Prediction Probability: 0.67 ⚠️ Risk Level: Borderline Risk Model Prediction: Diabetic

🔎 Key Risk Factors:

Glucose: 130.0 ↑ (increases risk) High glucose levels can indicate diabetes.

BMI: 32.0 ↑ (increases risk) BMI above 30 is classified as obese, increasing diabetes risk.

Age: 45.0 ↑ (increases risk) Risk of type 2 diabetes increases with age.
---
## 📦 Requirements

- Python 3.6+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🛠️ Installation
Follow these steps to set up and run the project on your local machine:

### 1. Clone the Repository
git clone https://github.com/your-username/diabetes-risk-prediction.git
cd diabetes-risk-prediction
### 2. Install Dependencies
Make sure you have Python 3.6 or higher installed. Then, install the required Python packages using pip:
pip install pandas numpy matplotlib seaborn scikit-learn
💡 Alternatively, you can use the provided requirements.txt file if available:
pip install -r requirements.txt
### 3. Run the Application
To start the diabetes prediction tool, run:
python diabetes_prediction.py

📊 Data Source  
This project uses the Pima Indians Diabetes Dataset, which contains medical information for 768 female patients of Pima Indian heritage, along with whether they developed diabetes within 5 years.

**Dataset Download:**  
You can download the Pima Indians Diabetes Dataset from [Kaggle here](https://www.kaggle.com/uciml/pima-indians-diabetes-database).

📥 Dataset Preparation:
1. Download the dataset from the provided link.
2. Place the `diabetes.csv` file in the root directory of the project folder.

## 📈 Key Visualizations

- **Feature Distributions:** Histograms showing how key features differ between diabetic and non-diabetic patients  
- **Correlation Matrix:** Heatmap showing relationships between different medical measurements  
- **Risk Score Distribution:** Histogram showing how the composite risk score separates diabetic from non-diabetic patients  
- **Confusion Matrix:** Visualization of the model's prediction performance  
- **Feature Importance:** Bar chart showing which features are most important for predictions

🎓 Educational Value
- Beyond predictions, this system aims to educate users about diabetes risk factors. For each prediction, it explains which factors are most concerning and why they matter.

🚧 Future Improvements
- Add more detailed medical guidance for risk factors
- Classifications based on Type1 or Type2
- Implement more sophisticated risk stratification
- Create a web interface for easier access (e.g., using Streamlit)
- Add option to save patient records and track changes over time

👩‍💻Contact 
Shruti Sharma 
[LinkedIn Profile](https://www.linkedin.com/in/shruti-sharma007)
