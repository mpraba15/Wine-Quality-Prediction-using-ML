## Introduction:
K-Nearest Neighbors (KNN) is a supervised machine learning algorithm used for both classification and regression tasks.
It is simple yet powerful and relies on the idea of similarity or distance between data point
This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm to predict wine quality based on various physicochemical properties using the Wine Quality dataset.

## Dataset Loading:

Uses sklearn.datasets.load_wine() to load the Wine dataset.

Converts it into a Pandas DataFrame for better visualization.
## Data Preprocessing:

Splits data into training and testing sets (train_test_split).

Applies feature scaling using StandardScaler().

## KNN Model Training:

Trains a KNeighborsClassifier with n_neighbors=3.

Uses the training set for fitting.

## Predictions & Evaluation:

Predicts test set labels.
Evaluates performance using:

Accuracy Score,
Classification Report,
Confusion Matrix

## Visualization:

Likely includes seaborn and matplotlib for data exploration and result visualization.

