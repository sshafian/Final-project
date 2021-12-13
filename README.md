# Final-project
This project will be mainly used for the Applied Data Science Capstone, which is the icing on the cake of the DataSc Professional certificate by IBM.

# Introduction
Road traffic injuries are currently estimated to be the eighth leading cause of death across all age groups globally, and are predicted to become the seventh leading cause of death by 2030.

Analysing a significant range of factors, including weather conditions, special events, roadworks, traffic jams among others, an accurate prediction of the severity of the accidents can be performed.

These insights, could allow law enforcement bodies to allocate their resources more effectively in advance of potential accidents, preventing when and where a severe accidents can occur as well as saving both, time and money. In addition, this knowledge of a severe accident situation can be warned to drivers so that they would drive more carefully or even change their route if it is possible or to hospital which could have set everything ready for a severe intervention in advance.

Governments should be highly interested in accurate predictions of the severity of an accident, in order to reduce the time of arrival and thus save a significant amount of people each year. Others interested could be private companies investing in technologies aiming to improve road safeness.

This project consist of several parts divided in two different notebooks.

# Feauter Selection
This first notebook contains all the steps and transformations I performed for the feature selection. You can find the information on the raw data in the following kaggle page. The kaggle datasets contain an extended descriptions of different aspect of the accidents, thus I've selected the most relevant and useful data for my analysis.

# Predicting Traffic Accident Severity
- Data Description
- Data Cleaning 
- EDA 
- Model Development
   * Random Forest 
   * Logistic Regression 
   * KNN 
   * SVM 
- Results

| Algorithm             |    Jaccard    | f1-score  | Precision |  Recall | Time(s) |
| -------------         | ------------- | ----------| --------- |---------|---------|
| Random Forest	        | 0.722         | 0.72      |0.72       |0.59     |6.58     |
| Logistic Regression	  | 0.66          | 0.65      |0.667      |0.45     |6.53     |
| KNN                   | 0.664         | 0.66      |0.652      |0.506    |200.58   |
| SVM                   | 0.659         |  0.65     |0.63       |0.528    |403.92   |
