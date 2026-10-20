
# Iris Flower Classification

## Project Overview
This beginner-friendly machine learning project predicts the
species of an Iris flower using four measurements:
sepal length, sepal width, petal length, and petal width.

Two classifiers are trained and compared:
- Decision Tree
- K-Nearest Neighbors (KNN)

## Dataset
The Iris dataset is provided by scikit-learn.

Dataset information:
https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html

It contains 150 examples, four numerical features, and three
flower species.

## Technologies Used
- Python
- Jupyter Notebook
- pandas
- matplotlib
- scikit-learn

## Setup and Execution
1. Install Python and Jupyter Notebook, or open Google Colab.
2. Open `iris_flower_classification.ipynb`.
3. Run the notebook cells from top to bottom.

Required Python libraries:
- pandas
- matplotlib
- scikit-learn

In a local Python environment, install them using:

    pip install pandas matplotlib scikit-learn

## Results

| Model | Test Accuracy |
|---|---|
| Decision Tree | 0.9333333333333333 |
| KNN | 0.9333333333333333 |

Both models were evaluated using a held-out test set and
confusion matrices.

## Conclusion
The model with the higher test accuracy performed better
on this experiment. This project demonstrates the basic
machine learning workflow: data preparation, model training,
prediction, and evaluation.
