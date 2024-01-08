# Room Occupancy Estimation Project

## Overview

This repository contains the code and documentation for my Room Occupancy Estimation Project. The project focuses on utilizing machine learning techniques to estimate room occupancy based on multivariate sensor data.

## Project Highlights

- **Objective:** The main goal of this project is to predict room occupancy using a variety of sensor inputs, including temperature, light, sound, and more.

- **Technologies Used:**  
  - Python
  - scikit-learn
  - pandas
  - matplotlib
  - seaborn
  - Jupyter Notebooks

- **Models Implemented:**  
  - Support Vector Machines (SVM)
  - Random Forest

- **Key Steps:**
  - **Exploratory Data Analysis (EDA):** Analyzed and visualized the dataset to gain insights into temporal patterns and feature distributions.
  - **Data Preprocessing:** performed feature engineering, and addressed class imbalance.
  - **Model Training:** Implemented and trained Support Vector Machines (SVM) and Random Forest models for occupancy estimation.
  - **Hyperparameter Tuning:** Utilized GridSearchCV to find optimal hyperparameters for the Random Forest model.
  - **Evaluation:** Employed various metrics, including accuracy, F1 score, and confusion matrix, to assess model performance.
  - **Cross-Validation:** Implemented TimeSeriesSplit to ensure temporal order preservation during model evaluation.

## Project Structure

├── data/  
│ ├── Occupancy_Estimation.csv  
├── doc/  
│ ├── Literature Review, Data Description, and Project Approach.pdf  
│ ├── Machine Learning-Based Occupancy Estimation.pptx  
├── src/  
│ ├── CIND820-Big Data Analytics Project(Occupancy_Estimation).ipynb  
├── LICENSE  
├── Project Phases Graph.png  
├── README.md  

## Usage
   git clone https://github.com/masram-ml/rpstry-bdap-occup-estmt-
   

## Acknowledgments  
The project is a replicating and learning based on the **Machine learning-Based Occupancy Estimation using Multivariate Sensors Nodes** : 
  - Adarsh Pal Singh, Vivek Jain, Sachin Chaudhari, Frank Alexander Kraemer, Stefan Werner and Vishal Garg, "Machine Learning-Based Occupancy Estimation Using Multivariate Sensor Nodes," in 2018 IEEE Globecom Workshops (GC Wkshps), 2018
