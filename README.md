# IPL_First_Inings_Prediction

**About**

This project predicts the first-innings score in IPL matches using ball-by-ball data. The dataset contained around 76,000 deliveries, and I applied regression models to estimate the final score.


**Steps I Followed**

Cleaned the dataset (removed extra columns, kept consistent teams, fixed dates)

Used features like overs, runs scored, and wickets

Trained models: Linear Regression, Decision Tree, Random Forest

Evaluated models using : Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE)


**Results**

The models gave fairly good predictions

Linear Regression → MAE: 12.12, RMSE: 15.84

Decision Tree → MAE: 17.25, RMSE: 23.21

Random Forest → MAE: 13.77, RMSE: 18.20

Linear Regression performed the best
Decision Tree was the weakest


From the analysis, I observed that early wickets and run rate have a strong impact on the final score
