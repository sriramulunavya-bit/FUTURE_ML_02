# Customer Support Ticket Classification

## Overview

This project uses Machine Learning and Natural Language Processing (NLP) techniques to automatically classify customer support tickets into predefined categories based on the issue description.

The model is trained using a customer support ticket dataset and uses TF-IDF vectorization along with a Linear Support Vector Machine (SVM) classifier to predict ticket categories.

## Features

* Data preprocessing and cleaning
* Text vectorization using TF-IDF
* Ticket category prediction using Linear SVM
* Model evaluation using accuracy score
* Confusion matrix visualization
* Organized project structure for deployment and future enhancements

## Project Structure

FUTURE_ML_02/

├── data/

│   └── customer_support_tickets.csv

├── images/

│   └── confusion_matrix.png

├── notebooks/

│   └── customer_support_ticket.ipynb

├── requirements.txt

└── README.md

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Dataset

The dataset contains customer support tickets with the following fields:

* Issue Description
* Category
* Product
* Priority

The model uses the issue description text as input and predicts the corresponding ticket category.

## Workflow

1. Load and preprocess the dataset.
2. Convert ticket descriptions into numerical features using TF-IDF.
3. Split data into training and testing sets.
4. Train a Linear SVM classifier.
5. Evaluate model performance.
6. Visualize results using a confusion matrix.

## Model

Algorithm Used:

* Linear Support Vector Classifier (LinearSVC)

Vectorization:

* TF-IDF Vectorizer

## Results

The model performance is evaluated using:

* Accuracy Score
* Confusion Matrix

## Installation

```bash
pip install -r requirements.txt
```

## Run the Project

```bash
jupyter notebook customer_support_ticket.ipynb
```

## Future Improvements

* Deploy as a web application using Flask or Streamlit.
* Add deep learning models such as LSTM or BERT.
* Implement real-time ticket routing.
* Add sentiment analysis for customer feedback.

## Author

SRIRAMULU NAVYA SREE
