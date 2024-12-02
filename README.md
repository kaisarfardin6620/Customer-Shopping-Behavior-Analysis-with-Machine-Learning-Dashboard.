***Customer Shopping Behavior Analysis***


To begin with, the dataset was preprocessed by handling null values, removing duplicates, and examining the data's structure, including shape, types, and 
descriptive statistics. Exploratory Data Analysis (EDA) was performed to understand the relationships between features and visualize patterns such as
distributions, correlations, and trends. Feature engineering included selecting relevant predictors, encoding categorical variables (e.g., Gender, Season),
and scaling numerical features for models that require normalization (like KNN and SVM). For clustering, customer segmentation was performed using
algorithms like K-Means (with the optimal number of clusters determined via the Elbow Method) and optionally DBSCAN for irregular groups, with
visualizations like PCA and t-SNE aiding in dimensionality reduction for better cluster representation.

For classification, the target variable was Subscription Status (Yes/No), with features like Age, Purchase Amount, and Frequency of Purchases selected as
predictors. The data was split into training and testing sets, and various algorithms—Logistic Regression, Random Forest, Decision Tree, KNN, and SVM—were
applied. Model performance was evaluated using metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrices, while feature importance and
ROC curves were used for additional insights. For regression, the target variable was Purchase Amount (USD), and features such as Age, Frequency of 
Purchases, and Review Rating were used. Algorithms like Linear Regression, Random Forest Regressor, Decision Tree Regressor, KNN, and SVR were implemented,
with performance assessed using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-Squared (R²).
