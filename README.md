# data-science-projects
Trying out various Data Science Projects for learning 

## Projects :

### 1. House Price Prediction 
loaded and explored the house price dataset, handling missing values and preparing categorical features using One-Hot Encoding. We then trained and           evaluated three regression models (SVM, Random Forest, and Linear Regression) for house price prediction, finding that the Random Forest model                performed best based on Mean Absolute Percentage Error.

### 2. Credit Card Fraud Detection
In this project focused on credit card fraud detection using a highly imbalanced dataset, we loaded and analyzed the data, identifying the significant class imbalance. We then trained a RandomForestClassifier model and evaluated its performance using various metrics. While accuracy was high due to the imbalance, key learnings from precision, recall, and F1-score revealed the model's ability to detect fraud effectively, highlighting the importance of using appropriate metrics for imbalanced datasets and suggesting that addressing the class imbalance could further enhance the model's recall.

### 3. Customer Segmentation
Performed unsupervised customer segmentation using K-Means. It involved data preprocessing, feature engineering, and applying t-SNE for visualization. The optimal number of clusters was determined using the elbow method. K-Means was implemented to segment customers, and the results were visualized, providing insights for targeted strategies.

### 4. Sales Forecast Prediction
A sales forecasting task was performed using the XGBoost machine learning model. The time-series data was preprocessed, lagged features for forecasting were created, an XGBoost model was trained, and its performance was evaluated using RMSE. This demonstrates a common approach in data science for time-series prediction problems.

### 5. Recommendation System
we built a movie recommendation system using collaborative filtering. We loaded and analyzed movie rating data, performed statistical analysis on user and movie ratings, created a user-item sparse matrix, and implemented a KNN-based approach to find similar movies and recommend them to users based on their highest-rated movie.

### 6. Time Series Analysis & Visualization
In this notebook, we specifically analyzed stock price time series data. Key steps included visualizing daily and monthly 'High' price trends, employing the ACF plot to assess seasonality, and performing the ADF test which indicated non-stationarity. We then applied differencing, confirming its effectiveness in achieving stationarity through a subsequent ADF test, and used a moving average to smooth the data.


