# Credit-Card-Transactions-Fraud-Detection
Project Overview: This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset used is a real-world dataset containing transactions made by credit cards, with a classification of whether each transaction is fraudulent or not.

Dataset: The dataset used is creditcard.csv, which consists of a large number of transactions with various features. It has a highly imbalanced distribution of fraudulent vs. non-fraudulent transactions.

Data Preprocessing: This involves loading the dataset using Pandas, checking for missing values, handling them accordingly, and addressing the imbalanced data by splitting it into fraudulent and normal transactions. Feature scaling and selection are also part of this step.

Model Training: Logistic Regression is used as a baseline model. Other possible models can be explored, such as Decision Trees, Random Forest, and Neural Networks.

Model Evaluation: The performance of the model is assessed using accuracy, precision, recall, and F1-score. Techniques like SMOTE or class weighting are used to address the issue of imbalanced data.
Results and Insights: The model works perfectly as the training dataset accuracy score is not significantly larger or minuscule than the testing dataset. The model does not have issues with underfitting or overfitting.

How to Run the Project: Install the required dependencies using pip install -r requirements.txt. Run the Jupyter Notebook step by step. Evaluate the model’s performance and make necessary modifications.

Conclusion: This project demonstrates the effectiveness of machine learning techniques in detecting fraudulent transactions. Future improvements can include trying different models, tuning hyperparameters, and using deep learning techniques
