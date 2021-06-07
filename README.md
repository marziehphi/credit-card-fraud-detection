# Creditcard Fraud Detection
Predictive Maintenance via Anomaly Detection using Machine Learning.

Fraudulent credit card transaction is still one of the obstacles that companies and individuals are faced; it makes them lose billions of money. 

Credit card fraud detection could define as the unauthorixed usage of the card, unusual transaction behavior, or an inactive card. The importance of fraud detection is withdrawing illegal financial actions. 

# Dataset and Challenges
The dataset consists of +200k rows with 20+ features that have gone trough a PCA pipeline. Only time and amount variable contain non transformed features. The dataset is highly imbalanced, there is a lot of normal data in comparison with abnormal data. For instance, 90 percent of data points are included for one class and 10 percent for the other. It caused performance measures (aka standard optimiza-
tion criteria) not to be as effective.



## Notebook

- A Neural Network (NN) classifier built that can predict the class column of the transactions,
- Next part, we droped the class column of the dataset and trained three unsupervised machine learning model that assign the lable of anomalous.
- provided the performance metrics that is considered appropriate.
- Compared and dicussed two supervised and unsupervised approaches.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marziehphi/credit-card-fraud-detection/blob/master/notes/anomaly_detection_using_ml.ipynb)
