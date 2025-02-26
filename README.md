 🏡 Predictive Modeling of House Prices Using Machine Learning  

Project Overview  
Accurate house price prediction is crucial for buyers, sellers, and investors in the real estate market. This project applies **machine learning models** to analyze and predict house prices based on various factors such as location, size, amenities, and market conditions.  

The study evaluates multiple ML models and identifies the best-performing one for price prediction.  

Dataset  
The dataset contains 13,603 training samples and 6,700 testing samples, with 14 features influencing house prices.  

🔹 Key Features:  
- Date – Date of the home sale  
- Price – Target variable (house price)  
- Bedrooms & Bathrooms – Number of rooms  
- Living Area (m²) – Size of the apartment  
- Nice View & Perfect Condition – Property condition indicators  
- Grade – Construction quality index (1-5)  
- Has Basement, Renovated, Has Lavatory – Property attributes  
- Single Floor – Flag for single-story houses  
- Month – Sale month  
- Quartile Zone – Index of expensive zip codes (1-4)  

 Machine Learning Models Used  
✅ Ordinary Least Squares (OLS) Regression 
✅ K-Nearest Neighbors (KNN)  
✅ Decision Tree Regression  
✅ Support Vector Regression (SVR)  
✅ Neural Networks (NN) 

Evaluation Metrics  
To assess model performance, the following metrics were used:  
- RMSE (Root Mean Square Error) – Measures prediction error  
- MAE (Mean Absolute Error) – Average absolute error  
- MSE (Mean Squared Error) – Squared difference between predicted & actual values  
- R² (Coefficient of Determination) – Model's predictive power  

Model Performance Comparison 
| Model  | RMSE (Test) | MAE (Test) | Best Fit? |
|--------|------------|------------|------------|
| OLS Regression | 203,877 | 165,355 | ❌ |
| KNN (k=11) | 215,942 | 175,190 | ❌ |
| Decision Tree | 203,721 | 165,277 | ❌ (Overfitting) |
| Support Vector Regression (SVR) | 206,546 | 161,300 | ✅ |
|Neural Network | 203,901 | 165,313 | ❌ |


Key Insight: 
The SVR model performed best, balancing accuracy and generalization.  

Future Improvements
Optimize hyperparameters for SVR
Experiment with Random Forest & XGBoost
Improve feature engineering

🛠 Installation & Usage  
 🔹 Clone the Repository  
```sh
git clone https://github.com/yourusername/House-Price-Prediction.git
cd House-Price-Prediction
