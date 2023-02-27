# DS3---Datathon
Welcome to the DS3 Winter 2023 Datathon!
This dataset describes the usage data of 108 old batteries, where the "remaining usage life (RUL)" value - when the batteries will retire - is labelled for each battery. Your task is to predict the RUL value of 19 unknown old batteries based on their usage data.

### Enter the Competition
Submit your predicted RUL for 19 old batteries in the test dataset on Kaggle, your submission will be ranked by MSE (mean squared error).

The winner will be announced tonight during our Award Ceremony which starts at 7:30 pm.

## Dataset Description
### Training and test dataset
Full training and test dataset can be found here.

### Data Files on Kaggle
Featurized Data.csv is the featurized data and Remaining Useful Life for the 108 batteries used to train the model
Featurized Prediction Data.csv is the featurized data for creating the submission csv including the Cell ID (not to be used for model building but mandatory for Kaggle Evaluation)
For Creating a Time Series Model (More Challenging And Not Necessarily Better)
Time Series Data.csv is the time series data and Remaining Useful Life for the 108 batteries used to train the model
Time Series Prediction Data.csv is the time series data for creating the submission csv including the Cell ID (not to be used for model building but mandatory for Kaggle Evaluation)

### Evaluation
The evaluation metric for Kaggle Leaderboard is the mean squared error for the ground truth remaining useful lifetime (RUL) for the 19 batteries in the prediction dataset. ## What should I submit? To enter the Kaggle Leaderboard: your submission file (.csv) should contain two columns: Cell ID and Predicted Remaining Useful Life
