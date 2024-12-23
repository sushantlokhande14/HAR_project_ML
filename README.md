# Human Activity Recognition Using Machine Learning for Wearable Technology

This project focuses on classifying human activities based on sensor data collected from wearable devices. Various machine learning models, including Support Vector Machine (SVM), Long Short-Term Memory (LSTM), Random Forest (RF), and Light Gradient Boosting Machine (LightGBM), were implemented to evaluate their performance in predicting human activities from time-series data.

---

## **Overview**

Human Activity Recognition (HAR) involves identifying movements and activities such as walking, sitting, standing, and others based on sensor data collected from wearable devices. The goal of this project is to build machine learning models to classify six human activities using the UCI HAR dataset.

### **Key Activities**
- Walking
- Walking Upstairs
- Walking Downstairs
- Sitting
- Standing
- Laying

---

## **Features**
- **Dataset**: UCI HAR Dataset with 10,299 samples and 561 features extracted from smartphone sensors.
- **Sensor Types**: Accelerometer and gyroscope.
- **Key Outputs**: Activity classification using machine learning.
- **Best Model**: LightGBM with a classification accuracy of **99.37%**.

---

## **Dataset**
The HAR dataset contains data from 30 participants aged between 19 and 48 performing six different activities. Data was collected using a Samsung Galaxy S II smartphone, utilizing its built-in accelerometer and gyroscope to record dynamic information about movements.

Training Data: 70% of the dataset (7,352 samples).
Test Data: 30% of the dataset (2,947 samples).
Feature Types: Time-domain and frequency-domain signals with statistical features such as mean, standard deviation, and correlations.

## **Methodology**
Data Preprocessing:

Feature scaling and normalization.
Handling missing values (none found in the dataset).
Splitting into training and testing subsets.
Exploratory Data Analysis (EDA):

Visualizing class distributions and feature correlations.
Analyzing activity imbalances and sensor signal patterns.
Model Training and Evaluation:

Implementation of machine learning models.
Hyperparameter tuning for performance optimization.
Evaluation using accuracy, precision, recall, and F1 score.
Models Implemented:

Support Vector Machine (SVM)
Long Short-Term Memory (LSTM)
Random Forest (RF)
LightGBM
## **Performance Comparison:**

Comparative analysis to identify the best-performing model.
Visualization of confusion matrices and classification metrics.
Models and Results
Model	Accuracy	Highlights
Support Vector Machine (SVM)	96.40%	Effective in high-dimensional spaces; suitable for complex feature datasets.
Long Short-Term Memory (LSTM)	94.59%	Captures temporal dependencies; robust against overfitting.
Random Forest (RF)	97.91%	Ensemble method; stable performance with minimal overfitting.
LightGBM	99.37%	Best performer; excels in handling large datasets with complex feature spaces.
Key Insights
Boosting Techniques: Models like LightGBM demonstrated superior performance due to their ability to iteratively refine predictions.
Sequential Dependencies: LSTM effectively captured temporal relationships, making it robust in generalization.
Ensemble Methods: Random Forest and LightGBM performed exceptionally well, showcasing the importance of ensemble approaches in HAR tasks.
Future Work
Real-Time Deployment:
Integrate the model into wearable devices for real-time activity monitoring.
Advanced Architectures:
Explore hybrid models and Transformer-based architectures for improved sequential data processing.
Efficiency Optimization:
Optimize for computational efficiency to enable edge-device deployment.
Broader Applications:
Extend HAR applications to fields like healthcare, fitness tracking, elderly care, and sports performance analysis.

## **References**
The project is based on data and techniques cited in the HAR Project Report. Key references include:

UCI HAR Dataset
Research papers on HAR and machine learning algorithms (see full list in the report).


## **Contributors**
Sushant Rakesh Lokhande
MS Computer Science, San Jose State University
Fall 2024
Project for CS 271
Feel free to fork, contribute, or raise issues for discussions!
