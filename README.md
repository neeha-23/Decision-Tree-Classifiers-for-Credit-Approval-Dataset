Project Title: Decision Tree Classifiers for Credit Approval Dataset
This project implements C4.5 and CART decision tree algorithms from scratch to classify credit card applications using the UCI Credit Approval dataset.
Project Title: Decision Tree Classifiers for Credit Approval Dataset
This project implements C4.5 and CART decision tree algorithms from scratch to classify credit card applications using the UCI Credit Approval dataset. The project is implemented in Google Colab and includes handling missing values, 10-fold cross-validation, and evaluation of the models on a test set.

Table of Contents
Project Overview

Requirements

Dataset

How to Run the Code in Google Colab

Code Structure

Output

Troubleshooting

Project Overview
The goal of this project is to implement and compare two decision tree algorithms:

C4.5: Uses information gain ratio for splitting.

CART: Uses the Gini index for splitting.

The dataset contains 690 examples with 15 attributes (9 categorical, 6 continuous) and missing values. The dataset is split into:

Training set: 550 examples (80%)

Test set: 140 examples (20%)

The project includes:

Handling missing values using the median for numerical attributes and the sorted median for categorical attributes.

10-fold cross-validation to select the best model.

Evaluation of the models on the test set using accuracy, precision, recall, and F1 score.

Requirements
To run this project in Google Colab, you need:

A Google account to access Google Colab.

The dataset files (training.data and test.data) uploaded to Google Colab.

No additional libraries need to be installed, as Google Colab comes pre-installed with numpy, pandas, and matplotlib.

Dataset
The dataset used in this project is the UCI Credit Approval Dataset. It contains 690 examples with 15 attributes (9 categorical, 6 continuous) and missing values. The dataset is split into:

Training set: training.data (550 examples)

Test set: test.data (140 examples)

The dataset files (training.data and test.data) should be uploaded to Google Colab.

How to Run the Code in Google Colab
Open Google Colab:

Go to Google Colab.

Sign in with your Google account.

Create a New Notebook:

Click on File > New Notebook to create a new Colab notebook.

Upload the Dataset Files:

Click on the folder icon in the left sidebar to open the file explorer.

Click the upload button and upload training.data and test.data.

Copy and Paste the Code:

Copy the entire code from your Python script and paste it into a code cell in the Colab notebook.

Run the Code:

Click the Run button (or press Shift + Enter) to execute the code cell.

The code will load the dataset, preprocess it, train the models, and evaluate them on the test set.


