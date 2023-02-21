# kaggle-titanic Competition Notebook
This repository contains a Jupyter Notebook for the [Kaggle Titanic competition](https://www.kaggle.com/competitions/titanic/data), which aims to predict survival rates for passengers aboard the Titanic based on various demographic and passenger features.

## Dataset
The dataset used in this competition contains demographic and passenger information for 891 of the 2224 passengers and crew on board the Titanic, which sank after hitting an iceberg in 1912. The dataset includes information such as age, sex, class, fare, and survival status.

## Notebook Overview
The Jupyter Notebook contained in this repository uses Python and various data analysis libraries to perform exploratory data analysis and build a predictive model to determine passenger survival rates. 
In this notebook we explore data in order to select most important feature. We also remove missing values, engineer new features, and prepare the data for model training and evaluation. And finally we tested differents models such as SVC, Random Forest, Naive Bayes.

## Prerequisites
To run the notebook, you will need the following libraries and tools:

- Python 3.11 or later
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- pipenv

## Usage
To run the notebook, clone the repository. Launch your virtual envirement with pipenv. use the Pipenv.lock to install packages. Launch Jupyter Notebook and open the notebook file `(TitanicV2.ipynb)`. Run the cells in order to reproduce the results and analyses presented in the notebook.

## Score
_21 feb 2023_
- **Score: 0.77990**
- **Place: 2890/13959 20,7%**

## Author
- [Thibaud Perrin](https://github.com/thibaud-perrin)