# LSTM-CNN-SOC

Stock market prediction by using CNN-LSTM neural network. Using more features makes an improvement to the accuracy. Plot of predicted vs actual values on the last 30 days-.
Best accuracy achieved is 96.4%

![output](https://github.com/parthgoel17/LSTM-CNN-SOC/assets/119148715/f12bc7d5-4495-4b99-bda8-c8b7c25edfd3)

Plot of predicted vs actual values for following week - 
Accuracy - 99.14%
![week](https://github.com/parthgoel17/LSTM-CNN-SOC/assets/119148715/ed94a1cf-18ae-4c73-9054-d0d849c20dd6)

Plot of predicted vs actual values for following fortnight - 
Accuracy - 98.3%
![image](https://github.com/parthgoel17/LSTM-CNN-SOC/assets/119148715/4270d099-3785-4779-a78d-18205ca3f303)

Libraries Used - Keras(for creating the model), sklearn (for feature selection and pre-processing),pandas ,matplotlib ,numpy
Data source - Collected features for the stock AAPL (Apple Inc.) using yfinance. Used more common stock indicators and performed feature selection using linear regression to filter the important features. 

Data pre-processing - Scaled the values so that it is easier for the model to recognize changes more easily. Eventually used a windowed dataset with the window size also being a hyperparameter (32,64,100 were also tested).

Architecture - 

<img width="564" alt="Screenshot 2024-06-23 at 20 11 04" src="https://github.com/parthgoel17/LSTM-CNN-SOC/assets/119148715/58e7cd0b-b1df-4af9-abef-f76ac3705391">

