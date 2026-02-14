# 🚢 Titanic Survival Prediction

## 📖 Project Overview

This Machine Learning project predicts whether a passenger survived the Titanic disaster using classification algorithms.

The model is trained on passenger information such as age, gender, ticket class, fare, and embarkation port.

---

## 📂 Dataset Information

The dataset contains the following important features:

- **Pclass** – Passenger Class  
- **Sex** – Gender  
- **Age** – Age of passenger  
- **SibSp** – Number of siblings/spouses aboard  
- **Parch** – Number of parents/children aboard  
- **Fare** – Ticket fare  
- **Embarked** – Port of embarkation  
- **Survived** – Target variable (0 = No, 1 = Yes)

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns:
  - PassengerId
  - Name
  - Ticket
  - Cabin
- Handled missing values:
  - Age → filled using median
  - Embarked → filled using mode
- Converted categorical variables using One-Hot Encoding
- Applied Feature Scaling (StandardScaler) for Logistic Regression
- Performed Train-Test Split (80% training, 20% testing)

---

## 🤖 Machine Learning Models Used

### 1️⃣ Logistic Regression
- Linear classification model
- Requires feature scaling
- Used as baseline model

### 2️⃣ Random Forest Classifier
- Ensemble learning algorithm
- Handles non-linear relationships
- Provides feature importance
- Does not require scaling

---

## 📊 Model Evaluation Metrics

The following metrics were used:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score

---

## 📈 Model Performance

| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | ~80%     |
| Random Forest          | ~85%     |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 📁 Project Structure

Titanic-ML-Project/
│
├── titanic.csv
├── Titanic_Model.ipynb
├── README.md
└── requirements.txt


---

## 🚀 How to Run the Project

1️⃣ Clone the repository:

git clone https://github.com/pysverma/Titanic-ML-Project.git

2️⃣ Navigate to project folder:

cd Titanic-ML-Project

3️⃣ Install dependencies:

pip install -r requirements.txt

4️⃣ Open the notebook and run all cells.

---

## 🎯 Key Learning Outcomes

- Data Cleaning & Preprocessing
- Handling Missing Values
- Feature Encoding
- Feature Scaling
- Logistic Regression
- Random Forest
- Model Evaluation Techniques
- Confusion Matrix Interpretation

---
