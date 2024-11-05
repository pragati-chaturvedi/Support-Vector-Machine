# Iris Dataset Classification with SVM
This Jupyter Notebook classifies the Iris dataset using a Support Vector Machine (SVM) model. It covers data loading, preprocessing, model training, and evaluation.

## Requirements
- Python 3.x
-  Jupyter Notebook
-  Required Libraries:
    * pandas
    * numpy
    * scikit-learn
    * matplotlib
- The Iris dataset is sourced from sklearn.datasets. It includes three species of iris flowers with 50 samples each and measurements for sepal length, sepal width, petal length, and petal width.

## Model Used
### Support Vector Machine (SVM)
Different configurations for parameters like gamma and kernel types (linear, polynomial) are tested to determine the best setup.

## Structure
Data Loading - Loads the Iris dataset using sklearn.datasets.load_iris.
Exploratory Data Analysis - Provides a brief overview and visualization of the dataset.
Model Training - Trains and evaluates the SVM model with various parameters.
Evaluation - Evaluates model performance with accuracy scores on test data.

## Usage
1. Open the Jupyter Notebook and execute each cell in sequence.
2. Adjust SVM parameters as desired to observe different results.

## Results
The notebook displays model performance based on accuracy scores, providing insights into the impact of parameter variations on classification accuracy.
