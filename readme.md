# Tutorial modeling data used car auction

Tutorial ini akan mengolah data Used Car Auction Prices menjadi data yang siap untuk dilakukan pemodelan

## Prerequisites

1. Download data [here](https://www.kaggle.com/datasets/tunguz/used-car-auction-prices?select=car_prices.csv)
2. Instalasi dengan pip install requirements.txt

## Getting started

-Dataset Splitting
-Training
-Model Validation

### Dataset Splitting

split data into training, validation and test sets
'''code
x_train, y_train,x_test, y_test=dataset_splitting()
x_train.shape,y_train.shape
'''

## Reference

1. Di scikit-learn documentain
