# Machine-learning-project-checklist
- We are required to deal with so many elements in a project (wrangling, preparation, questions, models, fine-tuning, etc.), it’s easy to lose track of things.
- Checklist guides us to check if every task has been executed successfully or not.

## Steps
### 1. Understanding the problem statement:
     1. Classifying the problem 
       - SUPERVISED
          - Classification
          - Regression
       - UNSUPERVISED
     2. Understanding the metadata
     3. Understanding the inherent assumptions of the data
     4. Identifying the Target variable and independent variables.
### 2. Data collection
     1.In most cases, this step can be executed before the first step if data is available.
     2.Based on the project and usecase, data could be collected from databases, surveys, sensors and data from clients.
### 3. Data Cleaning 
     1. Removing or imputing:
      - Missing values / Null values
      - Duplicate values
      - Imputation based on the data types
      - Outlier detection and treatment
### 4. Exploratory Data Analysis (EDA)
   - Data visualization tools and packages ( Matplotlib, Seaborn, Plotly, Tableau)
     1. Understanding the underlying distributions and patterns in the data
     2. Univariate analysis
     3. Bivariate analysis
     4. Multivariate analysis
### 5. Feature Engineering
      1. Feature reduction  
      2. Creating features based on the patterns from EDA
      3. Turning large groups into smaller groups (Discretization)
      4. combining two or more features
      5. Identifying the important features (Feature selection)
       - Dimensionality reduction: with PCA(Principal Component Analysis)
       - statistical methods( chi square, pearson,spearman, ANOVA, kendall etc)
### 6. Data preprocessing
      1. Data scaling - Normalization, Standardization (Numerical)
      2. Data Encoding - One hot encoding, label encoding
      3. Data splitting - Train, Test , validation
       1. Training set (usually 70-80% of data): Model learns on this.
       2.Validation set (usually 10-15% of data): Model hyperparameters are tuned on this
       3.Test set (usually 10-15% of data): Models’ final performance is evaluated on this. 
### 7. Model selection
      - Choosing the algorithm based on the problem
      -  SUPERVISED
      - **Regression**
      1. KNN regressor
      2. Linear regression
      3. Decision Tree
      4. SVM
      - **CLASSIFICATION**
      1. KNN classifier
      2.Logistic regression
      3.Naive bayes theorem
      4.Decision tree
      5.SVM
      - ENSEMBLES
      1.Bagging - Random forest
      2.Stacking
      3.Boosting -  AdaBoost, Gradient Boosting Machines, XGBoost 
    
      - UNSUPERVISED
      1.K-means clustering
      2.K-means ++
      3.PCA (Dimensionality reduction)
### 8. Model validation   
      1. Checking Bias and Variance - Underfitting or Overfitting
      2. Regularization
      3. Hyper parameter tuning
      4. Cross Validation
### 9. Model Evaluation
      - Evaluation metrics
      1. Classification
           - Balanced dataset: Accuracy, Precision, Recall, F1, Confusion matrix, ROC- AUC
           - Imbalanced dataset: Confusion matrix, Accuracy
      2. Regression – MSE,MAE,R-squared,RMSE
### 10. Model deployment
      - Put the model into production and see how it goes.
### 11. Retrain the model
 


    
