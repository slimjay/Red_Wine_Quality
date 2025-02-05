# Red_Wine_Quality

## Project Overview
The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: http://www.vinhoverde.pt/en/ or the reference [Cortez et al., 2009].  Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

Use machine learning to determine which physiochemical properties make a wine 'good'!

## Data Source
This data was obtained from [Kaggle Wine Quality](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009). These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). 

## Acknowledgement
- Paulo Cortez
- A. Cerdeira
- F. Almeida
- T. Matos
- J. Reis

  ## Data Used
  - Data: Two datasets related to red and white variants of the Portuguese "Vinho Verde" wine. With over 12 columns and 1599 rows
  - Data Cleaning and Analysis: Python, Jupyter-notebook
  - Dependencies: Numpy, Pandas, Matplotlib, Seaborn, Sklearn-learn
  - Model: RandomForestClassifier

  ## Summary of Findings
1. No null value in the dataset
2. Discovered Volatile acidity is inversely proportional to quality of the wine
3. Discovered Citric Acid is directly proportional to the quality of the wine
4. Did Label Binarization to classify any number higher than 7 was Good wine and any number lower was bad
5. Trained the model using Random Forest Classifier
6. Split the data into features and target
7. Had a predictive test score of 94%
8. Built a predictive system to verify results 
