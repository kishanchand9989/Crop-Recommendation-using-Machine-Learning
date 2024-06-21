# Crop-Recommendation-using-Machine-Learning

Situation:

Context: Agriculture in India faces challenges such as soil erosion, climate change, and inefficient resource use.
Problem: Farmers often struggle to select the optimal crop for planting, leading to suboptimal yields and income.
Objective: Develop a machine learning-based model to predict the best crop to harvest based on various environmental and soil factors.

Task:

Role: As part of a four-member team, tasked with developing a predictive model and user interface.
Goal: Create a system that uses historical and real-time data to recommend crops for specific soil types and environmental conditions.
Responsibilities:
Data collection and preprocessing
Model development and evaluation
Feature engineering
Deployment and user interface design


Action:

Data Collection:
Collected 18 years of crop data from Maharashtra, including attributes like NPK soil nutrients, temperature, pressure, wind speed, and soil type.
Data Preprocessing:
Cleaned and transformed raw data to handle missing values and normalize features.
Exploratory Data Analysis (EDA):
Identified data imbalances and significant patterns, ensuring a representative dataset for model training.
Feature Engineering:
Applied techniques like One-hot Encoding and Label Encoding to handle categorical variables.
Model Development:
Explored algorithms such as Decision Tree, Random Forest, KNN, Naive Bayes, and XG Boost.
Evaluated models using metrics like accuracy, precision, recall, and AUC score.
Selected XG Boost as the best-performing model with an accuracy of 70% and AUC of 0.95.
Model Training and Evaluation:
Split data into training and testing sets.
Fine-tuned models using hyperparameter optimization.
Deployment and User Interface:
Developed a user-friendly web interface for farmers to input data and receive crop recommendations.


Result:

Impact:
The XG Boost model achieved an accuracy of 70% and AUC of 0.95, significantly aiding in accurate crop recommendations.
