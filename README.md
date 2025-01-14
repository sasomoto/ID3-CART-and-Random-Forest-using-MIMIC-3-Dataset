# ID3-CART-and-Random-Forest-using-MIMIC-3-Dataset
Applying ID3, CART and RANDOM FOREST on patient data for anomaly detection

Import Required Libraries

Import OS environment variables, Pandas, NumPy, TensorFlow, TensorFlow Decision Forests, and Keras libraries.
Data Exploration and Preprocessing

Load the patient data from the provided CSV files.
Conduct a thorough data exploration.
Perform data cleaning, normalization, feature engineering, and outlier detection to enhance data quality.
Implement ID3 Decision Tree Algorithm

ID3 Implementation using Scikit-Learn: Train an ID3 model using Scikit-Learn's DecisionTreeClassifier on Patient-1 dataset.
Custom ID3 Implementation: Write a custom implementation of the ID3 algorithm from scratch and train it on the Patient-1 dataset.
Performance Analysis: Analyze the performance of both ID3 implementations.
Implement CART Decision Tree Algorithm

CART Implementation using Scikit-Learn: Train a CART model using Scikit-Learn's DecisionTreeClassifier on the Patient-2 dataset.
CART Implementation using TensorFlow: Train a CART model using TensorFlow's CartModel on the Patient-2 dataset.
Performance Analysis: Analyze the performance of both CART implementations.
Compare ID3 and CART Algorithms

Compare the results from the ID3 and CART algorithms on both datasets.
Identify the strengths and weaknesses of each algorithm.
Train and Evaluate Random Forest Model

Train a Random Forest model using TensorFlow's Decision Forests library on the Patient-1 dataset.
Evaluate the model's performance on the Patient-1 test data.
Visualize the first tree in the trained model.
Visualize the Hypothesis Space

Produce a scatter plot of the MIMIC dataset to visualize the hypothesis space.
Implement and Analyze Gradient Boosted Decision Trees (GBDT)

Train GBDT models with various hyper-parameters on the Patient-2 dataset.
Compare the accuracy and log loss of the GBDT models to the Random Forest model.
Analyze the results, considering factors such as overfitting, underfitting, and the impact of hyper-parameter tuning.
Feature Importance Analysis

Implement feature importance measurement using the feature_importances variable for both Random Forest and GBDT models to find the relative importance of each feature.
