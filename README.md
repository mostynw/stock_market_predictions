# stock_market_predictions

Group project undertaken to evaluate the effectiveness of Neural Network (LSTM) predictions on the stock price of, in this case, Gold (ticker: GOLD). 

We had a real problem with the code in this one that we failed to resolve. The LSTM model would give appropriate predictions for Gold 50% of the time while the other 50% the predictions would flatline. Testing the same model for other ticker symbols such as TSLA (Tesla) would fail to bring about any predictions that were not flatlines. I feel that the flatlines were due to mistakes made in formatting the input shape and the reason for Gold working 50% of the time was because of data leakage but it was never resolved.  

Any ideas on this would be very much appreciated!
