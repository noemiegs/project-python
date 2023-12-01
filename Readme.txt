
# Polish Bankruptcy companies Project

->Overview:

This repository contains the code and findings from our project focused on predicting bankruptcy in Polish companies. 
The primary objective was to build a predictive model that could identify companies which has a risk of bankruptcy based on financial indicators.

->Task Accomplished:

The dataset used in this project is https://archive.ics.uci.edu/dataset/365/polish+companies+bankruptcy+data
(containing financial attributes and bankruptcy labels for Polish companies)

- Data Analysis : The notebook 'Project_python_Visualisation.ipynb' explores the dataset, visualizing key financial features, and understanding the distribution of our class(bankruptcy).

- Data Cleaning : The notebook details the steps taken to clean and preprocess the data, handling missing values, and encoding categorical variables(this part is present in notebook for visualisation and for machine learning.

-Machine Learning: The notebook 'Project_python_MachineLearning.ipynb'includes machine learning models and predictive analyses conducted.

-API Django: The mysite folder containing all the files to start the API with the visualisation and the machine learning models that we applied (follow the step on the Readme inside the folder)

- Conclusion: The pdf summarizes the in and outs of the problem, including model performance, key features influencing predictions and understanding the influence of financial features.

->Conclusions:

- Achieved a predictive model for bankruptcy.

- Identified key financial features contributing to the bankruptcy predictions.

- Evaluated model performance through metrics.

- Understand the financial indicators that significantly impact the bankruptcy.


->Dependencies:

- Python 3.9.7
- Jupyter Notebooks/Google colab
- Required Python libraries:
	Django:4.2
	pandas:1.5.3
	scipy:1.11.3
	plotly:5.15.0
	matplotlib:3.7.1
	numpy:1.23.5
	seaborn:0.12.2
	ipywidgets:7.7.1
	scikit-learn:1.2.2
	xgboost:2.0.2

