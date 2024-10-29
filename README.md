## Ubiquant Market Prediction

This project is coming from Kaggle competition of Ubiquant Market Prediction -- Make predictions against future market data. As it's said in the description:
```
In this competition, you’ll build a model that forecasts an investment's return rate. Train and test your algorithm on historical prices. Top entries will solve this real-world data science problem with as much accuracy as possible.
```

### Data

This dataset contains features derived from real historic data from thousands of investments. Your challenge is to predict the value of an obfuscated metric relevant for making trading decisions.

* row_id - A unique identifier for the row.
* time_id - The ID code for the time the data was gathered. The time IDs are in order, but the real time between the time IDs is not constant and will likely be shorter for the final private test set than in the training set.
* investment_id - The ID code for an investment. Not all investment have data in all time IDs.
* target - The target.
* [f_0:f_299] - Anonymized features generated from market data.

### Models

To explore the better prediction, I defined some different DNN (deep neural networks) architectures, and through which I created coresponding models, trained them and saved the best trained models for each model architectures, finally generated prediction by using the best model among the saved models.

## Supporting Packages and Machine Learning Algoritms
- Keras
- Tensorflow
- Pandas
- Deep Learning
- LSTM
