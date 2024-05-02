# Predicting Customer Churn in Credit Card Data using Deep Learning

## Overview
This project aims to predict customer churn in a credit card dataset using a deep learning artificial neural network (ANN). Customer churn, or customer attrition, refers to the phenomenon where customers stop doing business with a company. Predicting churn is crucial for businesses as it helps in identifying at-risk customers and taking proactive measures to retain them.

## Dataset
The dataset used in this project contains information about credit card customers, including features such as credit score, age, tenure, balance, number of products, etc. The target variable is whether the customer has exited the bank (1 for exited, 0 for not exited).

## Methodology
1. Data Preprocessing: The dataset underwent preprocessing steps including handling missing values, encoding categorical variables, and feature scaling.
2. Model Architecture: An artificial neural network (ANN) was constructed using TensorFlow and Keras. The model consisted of multiple dense layers with ReLU activation functions and a softmax output layer.
3. Model Training: The model was trained on the preprocessed dataset using an Adam optimizer and sparse categorical crossentropy loss function. Training was performed over multiple epochs with a batch size of 32.
4. Evaluation: The model's performance was evaluated on a separate test set using accuracy and loss metrics. Additionally, the training and validation loss and accuracy were plotted to assess model performance over epochs.

## Results
The trained model achieved an accuracy of 85% on the test set, indicating its effectiveness in predicting customer churn. The model's performance was visualized through accuracy and loss plots, demonstrating its ability to learn from the data and generalize well.

## Conclusion
Predicting customer churn in credit card data using deep learning techniques can provide valuable insights for businesses to improve customer retention strategies. By identifying customers at risk of churn, businesses can take proactive steps to retain them, ultimately leading to improved customer satisfaction and profitability.

## Technologies Used
- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Author
Umme Fahad
