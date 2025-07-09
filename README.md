# Apple-Stock-Price-Prediction Using LSTM

This project focuses on predicting the stock prices of Apple Inc. (AAPL) using Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN). LSTM models are particularly effective for sequential data like stock prices due to their ability to capture long-term dependencies.

##DATASET:
The dataset used for this project consists of historical stock price data for Apple Inc.

##METHODOLOGY:

Datapreprocessing: The raw stock price data is preprocessed to handle missing values, normalize the features, and create sequential input-output pairs suitable for training LSTM models.

Model Training: LSTM models are trained using the preprocessed data. The models are configured with appropriate hyperparameters and trained on a subset of the data. The training process involves optimizing the model parameters to minimize the prediction error.

Model Evaluation: The trained LSTM models are evaluated using a separate test dataset to assess their performance in predicting future stock prices. Evaluation metrics such as mean squared error (MSE) or root mean squared error (RMSE) are calculated to quantify the model's accuracy.

Prediction: Once trained and evaluated, the LSTM models are used to make predictions for future stock prices. These predictions provide insights into potential price movements and trends, aiding investors in making informed decisions.



##Repository Structure:

Data: 'AAPL.csv' contains the raw and preprocessed datasets used for training and testing.

Notebooks: 'Apple_Stock_Price_Prediction.ipynb' contains the google colab with code for data preprocessing, model training, evaluation, and visualization.

Models: Saved model checkpoints or files for the trained LSTM models.

README.md: This document providing an overview of the project and instructions for replicating the analysis.




##Usage:

-Clone the repository to your local machine.

-Install the required dependencies and libraries.

-Explore the Google colab and Python scripts to understand the data preprocessing, model training, and prediction process.

-Execute the colabs or scripts to preprocess the data, train the LSTM models, and make predictions for future stock prices.

-Analyze the model performance using evaluation metrics and visualize the predicted stock prices.

-Experiment with different hyperparameters, architectures, or features to improve the model's accuracy.



##Used Dependencies Library:


Library →	 Purpose

numpy 	→ Numerical operations

pandas	→ Data manipulation

matplotlib	→ Data Visualization

Scikit-learn	→ Data preprocessing(MinMaxScaler)

tensorflow	→ Building and training LSTM model


Short video of project link: https://drive.google.com/file/d/1OqpFjYgVECJF8avcOXwGkSnttIBee3Zt/view?usp=drivesdk

