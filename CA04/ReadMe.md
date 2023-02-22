# CA04 – Ensemble Models

## - Brief description of the purpose of your program and what it is doing
1. This program detects whether someone's income is above or below $50K/yr based on demographic data
2. Trains a different ensemble algorithms on the train set and runs a for loop to test and plot different numbers of estimators, comparing how they perform in terms of accuracy and AUC across each models
3. The best accuracy and AUC per model is stored in a Pandas DataFrame

## - Libraries are needed in the environment to be able to run the code
- `numpy`
- `re`
- `pandas`
- `sklearn`
- `pyplot` from `matplotlib`
- `sys`

## - What versions of various software/libraries are you using
Python version
3.9.7 | packaged by conda-forge | (default, Sep 29 2021, 19:20:46) 
[GCC 9.4.0]
Version info.
sys.version_info(major=3, minor=9, micro=7, releaselevel='final', serial=0)

NumPy version: 1.22.1
pandas version: 1.4.0
Matplotlib version: 3.5.1
scikit-learn version: 1.0.2

## - What dataset are you using and their source
Source: https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true

## - Acknowledgement and link to source code of anyone else’s code, if you are reusing them
Some of the code was generated by ChatGPT

## - How to install and run your code along with datasets to be able to run your program successfully
1. Download folder from GitHub containing Jupyter notebook ("CA04 – Ensemble Models")
2. Upload folder to coding environment: Google Colab or Jupyterhub.
3. Run