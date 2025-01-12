# Stock Price Prediction Using LSTM

## Overview
This project demonstrates a predictive analysis task focused on forecasting stock prices using a Long Short-Term Memory (LSTM) neural network. The aim is to predict the closing prices of a stock based on historical data, leveraging LSTM's capability to model sequential and time-series data effectively.

## Features
- **Data Preprocessing**: Handling missing values, scaling features, and splitting data into training and validation sets.
- **Model Architecture**: Utilizes an LSTM network to capture temporal dependencies in stock prices.
- **Prediction and Evaluation**: Generates predictions on validation data and compares them with actual prices using visualizations.
- **Visualization**: Plots actual vs. predicted stock prices to assess model performance.

## Dataset
The dataset consists of historical stock prices, including:
- Open price
- High price
- Low price
- Close price (target variable)
- Volume

## Methodology
1. **Data Preparation**:
   - Load and preprocess the dataset (e.g., handle missing values, scale features).
   - Create training and validation sets.

2. **Model Building**:
   - Design and train an LSTM model.
   - Use Mean Squared Error (MSE) as the loss function.

3. **Prediction**:
   - Make predictions on the validation set.
   - Visualize the predictions against actual values.

## Dependencies
To run the project, install the following libraries:
- Python 3.8+
- TensorFlow
- NumPy
- Pandas
- Matplotlib

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/saish20/StockPrediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd StockPrediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook `main.ipynb` to see the predictions.

## Results
The model successfully forecasts stock prices with predictions visualized alongside actual values. While LSTM captures trends effectively, further hyperparameter tuning and feature engineering could enhance performance.

## Improvements
- Add more features like market sentiment analysis or macroeconomic indicators.
- Experiment with different architectures such as GRU or attention mechanisms.
- Use hyperparameter optimization techniques like Grid Search or Bayesian Optimization.

## Conclusion
This project demonstrates the application of LSTM for stock price prediction, highlighting its ability to model sequential data effectively. With further refinements, this methodology could be adapted to various time-series forecasting tasks.

## Author
[Saish Mayekar](https://github.com/saish20)

---
Feel free to explore the repository for additional details and implementation specifics.
