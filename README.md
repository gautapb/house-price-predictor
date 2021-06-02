# house-price-predictor

This repo contains code for the house price prediction model

Few details about the model/methodology:

1. Dataset used: kaggle competition dataset: https://www.kaggle.com/c/house-prices-advanced-regression-techniques 
2. Detailed EDA is performed which is present in the EDA ipython notebook
3. Multiple models are tried before selecting the final one (xgboost)
4. Entity embeddings weights trained using neural network are used as xgboost features to see if there is any performance improvement (notebook: embeddings experiment)
5. libraries used: numpy, pandas, sklearn, xgboost, fastai
