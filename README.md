# cancer_prediction

**Cancer Prediction Using Multiple Machine Learning Models**

This project demonstrates the application of multiple machine learning models for predicting cancer diagnosis (benign or malignant). By evaluating various algorithms, it identifies the best-performing model based on accuracy.

**Features**

	•	Processes Breast Cancer Wisconsin Dataset for feature extraction and prediction.
	•	Evaluates multiple models, including SVM, Random Forest, Logistic Regression, Polynomial Regression, KNN, and more.
	•	Performs Grid Search for hyperparameter optimization to enhance model accuracy.
	•	Implements feature scaling and polynomial transformation for better predictions.
	•	Visualizes model performance for comparison and selection of the best-performing model.

**Dataset**

	•	The dataset used is the Breast Cancer Wisconsin Dataset.
	•	Includes 30 features extracted from cell nuclei, with a target label indicating whether the tumor is benign (B) or malignant (M).
	•	Download the dataset here.

**Requirements**

	•	Python 3.x
	•	Libraries:
	•	numpy
	•	pandas
	•	scikit-learn
	•	matplotlib

Install dependencies using:

pip install numpy pandas scikit-learn matplotlib

**Instructions**

	1.	Dataset Preparation:
	•	Place the dataset file named Cancer_Data.csv in the project directory.
	2.	Run the Code:
Execute the Python script to train and evaluate the models:

python cancer_prediction.py


	3.	Outputs:
	•	Displays a bar graph comparing cross-validation scores of different models.
	•	Prints the best-performing model with its hyperparameters and test accuracy.

**Code Overview**

The project workflow includes:
	1.	Data Preprocessing:
	•	Normalization and feature scaling.
	•	Splitting the data into training and testing sets (80-20 split).
	2.	Model Training and Hyperparameter Optimization:
	•	Implements Grid Search for algorithms like SVM, Random Forest, etc.
	•	Includes Polynomial Regression for nonlinear feature mapping.
	3.	Model Selection:
	•	Compares models based on cross-validation accuracy.
	•	Identifies and evaluates the best-performing model on the test set.
	4.	Visualization:
	•	Bar graph to showcase the performance of all models.

**Results**

	•	Outputs the name of the best model, its hyperparameters, and test accuracy.
	•	Visualizes cross-validation performance to identify trends across models.

