# Crypto Clustering
This project is a part of the Module 19 challenge in the Vanderbilt University Data Analytics BootCamp and is written entirely by the author of the repository. This README template is from the Data Science Working Group.

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to demonstrate proficiency in fundamental unsupervised learning techniques, such as utilizing the elbow method to find the appropriate amount of clusters, employing the K-means algorithm to create clusters from the data, and applying Principal Component Analysis to our dataset to reduce dimensionality. 

### Methods Used
* Unsupervised Machine Learning
* Data Visualization

### Technologies
* Python
* Pandas, jupyter
* Scikit-Learn

## Project Description
The data source for this project is generated by edX and intended for educational purposes. The first part of the project conducts some introductory EDA functions to understand the data. Next, the data is scaled using the StandardScaler method & the elbow method is employed to understand how many clusters make sense for the raw data. Then, a K-means model is fitted with the data and utilized to predict clusters for the data. Afterward, the original dataset is reduced in dimensionality from 7 to 3 dimensions using Principal Component Analysis. This reduced dataset is then put through the same workflow as the original dataset to understand the optimal k-value and resulting k-means analysis. Overall, the PCA model does a better job in visualizing the clustering of our cryptocurrency, but faces challenges in interpretting the significance of the principal components created from the original data.

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Jupyter Notebook script and analysis text are being kept in the forefront of the repo.
3. Raw Data is kept in the [Resources](Resources) directory.    

## Getting Started

1. Clone this repository (for help see this tutorial).
2. The Jupyter Notebook script (credit_risk_classification.ipynb) and the dataset (lending_data.csv) are located in the "Credit_Risk" folder.
3. Raw data is stored in the Resources directory.   
