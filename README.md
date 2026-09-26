# Titanic Survival Prediction Using Logistic Regression

## Project Overview

This project explores binary classification using Logistic Regression to predict the `Survived` label in a Titanic passenger dataset.

The project covers:

* Exploratory Data Analysis
* Data Preprocessing
* Feature Scaling
* Model Training
* Model Evaluation
* Feature Analysis

## Dataset

The notebook uses a Titanic passenger dataset containing 418 rows and 12 columns.

The target variable is `Survived`:

* `0` → Did not survive
* `1` → Survived

## Project Workflow

### 1. Exploratory Data Analysis

The dataset was explored by:

* Checking the dataset shape
* Checking data types
* Checking missing values
* Checking duplicate records
* Analyzing the target variable distribution
* Visualizing relationships between survival and passenger features
* Analyzing passenger class, sex, age, fare, and embarkation port

### 2. Data Preprocessing

The preprocessing steps include:

* Removing irrelevant columns such as `PassengerId`, `Name`, `Ticket`, and `Cabin`
* Handling missing values in `Age` and `Fare`
* Encoding categorical variables
* Scaling numerical features using `StandardScaler`

### 3. Train-Test Split

The dataset was divided into:

* 80% Training Data
* 20% Testing Data

`random_state = 42` was used to ensure reproducibility.

### 4. Model Training

The classification algorithm used in this project is:

**Logistic Regression**

Logistic Regression was used because the target variable represents a binary classification problem.

### 5. Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### 6. Feature Analysis

The model coefficients were analyzed to understand the relationship between the input features and the predicted survival outcome.

## Key Insights

* The target variable contains two classes: survived and did not survive.
* Female passengers had a higher survival rate in the analyzed dataset.
* Passenger class showed differences in survival rates.
* Age and Fare contained missing values that required preprocessing.
* Logistic Regression coefficients provide information about the relationship between features and the predicted outcome.
* The confusion matrix was used to analyze correct and incorrect predictions.

## Model Results

The notebook achieved the following results on the test set:

| Metric    | Result |
| --------- | -----: |
| Accuracy  |   100% |
| Precision |   100% |
| Recall    |   100% |
| F1-score  |   100% |

### Confusion Matrix

```text
[[50, 0],
 [ 0, 34]]
```

## Technologies and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
Titanic-Survival-Prediction/
│
├── Titanic_Logistic_Regression_Project.ipynb
├── README.md
└── tested.csv
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Titanic-Survival-Prediction.git
```

2. Navigate to the project directory:

```bash
cd Titanic-Survival-Prediction
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Open the notebook:

```bash
jupyter notebook
```

5. Run `Titanic_Logistic_Regression_Project.ipynb`.

## Author

**Soha Elzelaky**

Computer and Communications Engineering Graduate

Machine Learning and Data Analysis Enthusiast
