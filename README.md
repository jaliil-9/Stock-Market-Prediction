# Stock Market Prediction
The motivation for this project is to provide a more informed and data-driven approach to stock trading, which can potentially lead to higher profits and better investment decisions, and a trading bot that uses machine learning to predict optimal times to buy and sell Tencent stock. We chose to use Tencent's historical stock movement (0700.HK) data due to its consistent growth and stability, making it a reliable investment option.

# Project description
This potential project aims to develop a trading mechanism that can predict the high and low stocks of Tencent (0700.HK). We will then clean and preprocess the data then the argrelextrema method from the scipy.signal package, which locates local maximum and minimum values, will be used to extract and annotate the dataset. The machine learning model used will be a classification model with three classes: high, low, and neither.

# Training and validation
The model will be trained and validated using the Tencent (0700.HK) dataset, training will be on data from 2015-2018, and validation data will from 2019-2020, we will use f1 score to evaluate the model's performance.

# Trading bot
The final trading system will aim to maximize profit and have three parameters: g, l, and d. By altering these factors, the project will produce four distinct investor types: Short-term Investor, Medium-term Investor, Long-term Holder, and Random Investor. The smallest value of l will be held by the short-term investor, the middle-term investor will hold both l and g at an intermediate value, the long-term holder will hold the biggest value of g, and the random investor will hold g, l, and d at random values. The real business delivery will be applied on the testing data which is data from 2021.
