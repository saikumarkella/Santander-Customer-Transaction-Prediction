# Santander-Customer-Transaction-Prediction

### Aim : identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted.

***Observations:***
- Dataset was Imbalanced(1:9).
- Features are not highly correlated.
- Distriution of Features in test dataset have some difference as compared to the train dataset.
- many of the Feature are follows Normal distribution. and also have low skwed.

***Used Techniques:***
- To make the dataset in to balanced by using sampling methods(upsampling and downsampling).
- To increase speed of model did standardization.
- Feature Engineering (by adding some new derived features).

***Experiments:***
- Build the different models on both the balaced and imbalanced dataset.
- Models are Logistic Regression, naive Bayes, Random Forest, Decision Trees, XGboost, LightGBM.

***Result:***
[image](result.png)
