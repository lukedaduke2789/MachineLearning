# MachineLearning
# Social Network Ads - Machine Learning Project

## Objective
This project demonstrates the application of machine learning techniques to predict whether a user will purchase a product based on social network advertisement data. The project involves data preprocessing, exploratory data analysis (EDA), model implementation, and evaluation.

---

## Dataset
The dataset used in this project is **Social_Network_Ads.csv**, which contains the following columns:
- **User ID**: Unique identifier for each user.
- **Gender**: Gender of the user (Male/Female).
- **Age**: Age of the user.
- **EstimatedSalary**: Estimated salary of the user.
- **Purchased**: Target variable indicating whether the user purchased the product (0 = No, 1 = Yes).

**Source**: (Specify the source of your dataset, e.g., Kaggle, UCI Machine Learning Repository, etc.)

---

## Steps and Methodology

### 1. Exploratory Data Analysis (EDA)
- Conducted an initial exploration of the dataset using `head()`, `describe()`, and `info()` to understand the structure, data types, and summary statistics.
- Created visualizations (e.g., pair plot) to explore relationships between features and the target variable.

### 2. Data Preprocessing
- Encoded the **Gender** column into numeric values (0 = Male, 1 = Female).
- Standardized the **Age** and **EstimatedSalary** features using `StandardScaler`.
- Split the dataset into training (75%) and testing (25%) sets.

### 3. Model Implementation
- Selected Logistic Regression as the machine learning algorithm for classification due to the binary nature of the target variable.
- Trained the model using the training set.

### 4. Model Evaluation
- Evaluated the model using the test set and calculated performance metrics:
  - **Confusion Matrix**
  - **Precision, Recall, F1-Score**
- Results showed the model's ability to predict purchases based on user attributes.

---

## Results
- Confusion Matrix:
