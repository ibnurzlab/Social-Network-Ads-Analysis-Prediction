# Social-Network-Ads-Analysis-Prediction
This project focuses on analyzing and predicting user purchase behavior based on demographic information (Age, Gender, and Estimated Salary) using the **Social_Network_Ads** dataset. The goal is to understand customer segmentation and build a classification model that predicts whether a person will purchase a product after seeing an ad.

## 🗂️ Dataset
- **File:** `Social_Network_Ads.csv`  
- **Columns:**
  - `User ID`: Unique identifier of each user
  - `Gender`: Male/Female
  - `Age`: Age of the user
  - `EstimatedSalary`: Approximate salary of the user
  - `Purchased`: Target variable (0 = Not Purchased, 1 = Purchased)

## 🔍 Exploratory Data Analysis (EDA)
Several visualization techniques were used to understand the dataset:
- **Gender distribution** of users
- **Age distribution** in the dataset
- Scatter plots showing the relationship between:
  - Age vs Purchased
  - Estimated Salary vs Purchased
- Statistical summary of features

## 🧠 Machine Learning Approach
The notebook applies **classification algorithms** to predict purchase behavior.  
Typical workflow:
1. Data preprocessing (handling categorical features, scaling, splitting train-test)
2. Model training (e.g., Logistic Regression, SVM, Decision Tree, Random Forest, etc.)
3. Model evaluation using accuracy, confusion matrix, and visualization.

## 📊 Results
- The model can identify patterns between **Age & Salary** with **purchase decisions**.
- Helps businesses target specific demographics for marketing campaigns.

## 🛠️ Tech Stack
- **Python**  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn  
