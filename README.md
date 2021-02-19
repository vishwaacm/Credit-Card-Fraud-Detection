# Credit-Card-Fraud-Detection
A data science project (attached) explains the different techniques and methods in detecting the fraud and non-fradulant transactions using Python in Jupyter Note book. Note that this has been run in the local machine. Only partial data lines has been taken for the analysis.

This work includes:

    Exploratory Data Analysis: Histograms showing distribution of data by class. Check if the dataset is balanced or not.	
        
    Data processing: Deal with missing values, outliers
    Feature engineering: Get relevant features and ways to remove collinear features.
    Model and training the data set with different opitions mentioned in the conclusion.


Conclusion

Here, I have explored 8 different methods for dealing with imbalanced datasets (as this):

    o	Logistic Regression
  
    o	Random Forests
  
    o	K-nearest neighbours
  
    o	Support Vector Machine
    
Data handling/sampling techniques
  
    o	Optimisation using GridSearchCV
  
    o	Oversample minority class
  
    o	Undersample majority class
  
    o	Generate synthetic samples (SMOTE)

For highly unbalanced dataset (as this) using SMOTE with Random and Oversampling with Logistic Regression are the best of the options. Elbow method also gives improvement, howver might it need to whole data set into analysis. Might be many other possible methods to try when dealing with imbalanced datasets. Some others methods to consider more data set and choosing different resampling ratios may help in improving the score.
