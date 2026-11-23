# E-Commerce Product Return Prediction

A machine learning project that predicts whether an e-commerce order will be returned and identifies the possible reason for the return using customer, product, seller and transaction data.

## Technologies Used
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Dataset
- 30,000 e-commerce orders
- 42 original columns
- 36% of orders were returned

## Machine Learning Models
Four classification algorithms were implemented and compared:
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

A separate Random Forest model was used to predict return reasons across five categories.

## Key Results
- Best overall model: SVM
- Accuracy: 85.70%
- F1-score: 80.55%
- ROC-AUC: 93.21%
- Random Forest achieved the highest return recall of 85.97%.

## Features
- Data cleaning and preprocessing
- Feature engineering
- Model training and comparison
- Threshold selection using validation data
- Performance evaluation using accuracy, precision, recall, F1-score and ROC-AUC
- Feature importance analysis
- Return reason prediction

## Project Team
- Anagha S Prasad
- Asif Mohammed Ali
- Sajeer F M
- Twinkle Treesa

