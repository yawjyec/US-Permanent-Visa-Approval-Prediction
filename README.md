# US-Permanent-Visa-Approval-Prediction
This is Metis Project 3  
  
## Objective
The objective of this project is to predict the probability of US Permanent Visa approval. The data used for this project is from Kaggle and The World Bank. Due to the imbalanced classes in the dataset, oversampling was used to improve the performance of model prediction.

## Data Source
Link for data:  
https://www.kaggle.com/jboysen/us-perm-visas  
https://ourworldindata.org/ . 

## Source Codes
1.	Modeling.ipynb
*	This is the main notebook, which contains source code of data query from Postgresql, feature engineering, model evaluation & selection.
2.	Export_to_AWS.ipynb
*	This notebook is used to create tables in PoatgreSQL installed on AWS server.
3.  Data_Cleaning.ipynb
* This notebook is used for data preprocessing/cleaning. It also contains preliminary exploratory data analysis to provide insights before choosing features for data modeling.
4.  Data_Visualization.ipynb
* This notebook is used to create 3D visualization of correlation of 3 important features on visa approval.

## Final Product
Please see <US_Permanent_Visa_Prediction_Presentation.pdf > for final product of this project.

