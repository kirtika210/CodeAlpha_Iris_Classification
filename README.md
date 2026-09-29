# CodeAlpha Iris Flower Classification

## Project Overview

This project is completed as part of the **CodeAlpha Data Science Internship**.

The objective of this project is to build a Machine Learning model that classifies Iris flowers into three different species:

* Setosa
* Versicolor
* Virginica

The Iris dataset provided by **Scikit-learn** is used for this classification task.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Load the Iris dataset
2. Create a Pandas DataFrame
3. Explore the dataset
4. Check for missing values
5. Visualize the data
6. Split the dataset into training and testing data
7. Apply feature scaling
8. Train a Logistic Regression model
9. Make predictions
10. Evaluate model performance
11. Generate a classification report
12. Generate a confusion matrix
13. Test the model with a new flower

## Dataset

The Iris dataset contains four features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The target variable contains three flower species:

* Setosa
* Versicolor
* Virginica

## Machine Learning Model

**Logistic Regression** is used as the classification algorithm.

The dataset is divided into:

* **80% Training Data**
* **20% Testing Data**

`StandardScaler` is used for feature scaling before training the model.

## Model Evaluation

The following metrics are used to evaluate the model:

* Accuracy
* Precision
* Recall
* F1 Score
* Classification Report
* Confusion Matrix

## Sample Prediction

A new flower with the following measurements was given to the trained model:

| Feature      |  Value |
| ------------ | -----: |
| Sepal Length | 5.1 cm |
| Sepal Width  | 3.5 cm |
| Petal Length | 1.4 cm |
| Petal Width  | 0.2 cm |

### Prediction

**Predicted Flower Species: Setosa**

## Project Structure

```text
CodeAlpha_Iris_Classification/
│
├── dataset/
│
├── images/
│   └── confusion_matrix.png
│
├── notebook/
│   └── iris_classification.ipynb
│
├── .gitignore
├── README.md
└── requirements.txt
```

> Note: The `venv/` folder is kept locally but excluded from GitHub using `.gitignore`.

## How to Run the Project

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```

### 2. Open the project

```bash
cd CodeAlpha_Iris_Classification
```

### 3. Create a virtual environment

```bash
python3 -m venv venv
```

### 4. Activate the virtual environment

```bash
source venv/bin/activate
```

### 5. Install required libraries

```bash
pip install -r requirements.txt
```

### 6. Open the Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
notebook/iris_classification.ipynb
```

## Internship Task

This project is completed as part of the **CodeAlpha Data Science Internship – Iris Flower Classification Task**.

The task involves using Scikit-learn to build a model that classifies Iris flower species and evaluating its performance on test data.
