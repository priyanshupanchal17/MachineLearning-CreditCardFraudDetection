# MachineLearning-CreditCardFraudDetection

ABOUT
Credit card fraud detection is a critical application in the financial sector aimed at identifying unauthorized or suspicious transactions to prevent financial losses. With the rapid growth of online transactions, fraud detection systems have become essential to ensure the safety and trust of consumers and businesses. These systems leverage advanced technologies such as machine learning and artificial intelligence to analyze transaction patterns, detect anomalies, and classify transactions as legitimate or fraudulent. Features like transaction amount, location, time, and spending behavior are used to train predictive models. Real-time detection systems can flag suspicious activity almost instantly, minimizing risks. Despite advancements, challenges like false positives, data privacy concerns, and evolving fraud techniques necessitate continuous improvement of these systems to enhance accuracy and efficiency.

DATASET : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

OBJECTIVE
The project aims to provide various methods to analyse the cradit card fraud detections and decide on the most suitable approach to implement.

CONCLUSION
Different Models achieve different levels of accuracy or precision
Decision Tree : 0.83
Logistic Regression : 0.91
Random Forest : 0.94
SVM : 0.94

An Ideal and most optimal solution would be to use Random Forest Classifier along with Bagging techniques like XGBoost , CatBoost etc to further enhance the adaptability of the model to larger datasets.

