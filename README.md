# Housing Prices Competition

The Housinc Prices competition is a regression Machine Learning competition at Kaggle, in which the participants are challeneged to predict the prices of houses which are up to sale in Ames (a city in Iowa, USA).

The given dataset includes 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa, such as: number of floors / parking lot size / type of road access (gravel / paved) / available utilities / etc.

In this notebook I explain the steps I've done to build my model and achieve a good [RMSE](https://en.wikipedia.org/wiki/Root-mean-square_deviation) of 13,833 (the evaluation metric is the RMSE between the logarithm of the predicted value and the logarithm of the observed sales price. Taking logs have the benefits of robustness to outliers, relative instead of absolute error, and giving the same penalty for overestimated and underestimated prices).

Please find the notebook [**housing-prices.ipynb**](https://github.com/masalha-alaa/housing-prices/blob/master/housing-prices.ipynb) in the root directory, in which you'll find a complete walkthrough of my work, or head up to my [Kaggle profile](https://www.kaggle.com/alaamasalha/housing-prices) where you'll find the same notebook and see some of my other projects.

<img src="https://github.com/masalha-alaa/housing-prices/blob/master/docs/housing-prices-profile.png">


