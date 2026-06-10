# Titaniv survival prediction (SAM-AI-Internship)
Domain: 
Data Science Internship Projects
## 📌 About This Project
This project predicts whether a passenger on the
Titanic survived or not using Machine Learning.
Built as Task 1 of my Data Science Internship
at SAM AI Technologies.

## 🎯 Objective
Build a classification model that predicts
survival of Titanic passengers based on
features like age, gender, ticket class etc.

## 📊 Dataset
- Source: Kaggle Titanic Dataset
- Total Passengers: 891
- Features Used: 7
- Target: Survived (0=Died, 1=Survived)

## 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 📋 Steps Completed

### Step 1 — Data Preprocessing
- Loaded dataset (891 rows, 12 columns)
- Handled missing values in Age column
- Dropped Cabin column (77% missing)
- Filled Embarked missing values
- Renamed columns for clarity
- Converted text to numbers

### Step 2 — Data Visualization
- Chart 1: Survival Count Bar Chart
- Chart 2: Gender vs Survival
- Chart 3: Ticket Class vs Survival
- Chart 4: Age Distribution Histogram
- Chart 5: Fare Price Distribution
- Chart 6: Correlation Heatmap

### Step 3 — ML Model Building
- Selected 7 input features
- Split data: 80% train, 20% test
- Used Logistic Regression model
- Trained model on 712 rows

## ✅ Model Results
- Algorithm: Logistic Regression
- Training rows: 712
- Testing rows: 179
- Accuracy: 79.89%

## 📁 Files in This Repository
- Titanic_Data_Analysis.ipynb — Main notebook
- Titanic_dataset.csv.xlsx — Cleaned dataset

## 🏢 Internship Details
- Company: SAM AI Technologies
- Domain: Data Science
