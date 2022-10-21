# Anomaly detection
Anomaly detection is to identify the rare events or outliers. 
It is important to the various applications such as financial fraud. 
I study the examples by comparing the performance of the different methods.

## Methods
-	Oversampling + ML (Random Forest, XGBoost, LightGBM) 
-	Autoencoder and variational autoencoder
-	Deep Learning models (dense, lstm, cnn, bidirectional-lstm, cnn-lstm)
-	Unsupervised methods (OneClassSVM, IsolationForest, EllipticEnvelope, LocalOutlierFactor)

## Metrics:
-	Accuracy
-	F1-score
-	Jaccard Score
-	G-mean

## Example 1:
- Dataset: [Signal from Northern California Earthquake Data Center](http://www.timeseriesclassification.com/description.php?Dataset=Earthquakes)
- Outline: It is a binary classification problem to classify earthquake and non-earthquake signals. 
In this example, the variational autoencoder method gives the best performance.

## Example 2
- Data set: [Credit card fraud](https://www.kaggle.com/datasets/mishra5001/credit-card)
- Outline: The data contains the fraud and non-fraud cases, where the fraud event is rare. 
In this example, the DL models provide a higher accuracy and F1-score.
