#  ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2 - Singapore Housing Data and Kaggle Challenge

**Primary Learning Objectives:**
1. Creating and iteratively refining a regression model
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process
3. Providing business insights through reporting and presentation.


# Problem Statement
we will create a regression model base on singapore HDB Dataset to predict the price of a HDB unit. the mode will explain which features of the HDB flat effect the resalse price. We want to see if distance to school, mall, hawker center, mrt has an effort on the resale price. it is to help buyer to estimate the value of the unit before buying. the predicted resale prices will be summbit to[Kaggle](https://www.kaggle.com/) for scoring.


# Data set
* [`train.csv`](./datasets/train.csv): training data provided which contain all features and HDB resale prices
* [`test.csv`](./datasets/test.csv): test dataset will all features only. use to predict the HDB resale prices
* [`sample_sub_reg.csv`](./datasets/sample_sub_reg.csv): sumbition template for kaggle
* [`hdb_final_data.csv`](./datasets/hdb_final_data.csv): preprocesed data set for training
* [`pred.csv`](./datasets/pred.csv): preprocesed data set for model prediction
* [`lr.csv`](./datasets/lr.csv): data set for sumbition for kaggle


-
### Conclusions and Reecommendation:

For home buyer wanted to buy a flat, floor area sqft, distance to mall, distance to hawker center, age of flat and storey are the most infuential factor the determine the pirce. therefor if this is not a requirement to you, you may choose to choose hdb farer away from mall and hawker center it will reduce the overall price. lower floor area sqft and storey will also reduce the overall price. Sembawang and Woodland have a lower resale price compare to other town 

