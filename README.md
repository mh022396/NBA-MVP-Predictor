NBA-MVP-Predictor

This project webscrapes for data from https://www.basketball-reference.com/. Processes html to create all data. Then uses this data for making predictions on MVP share
using a number of regression models. These predictions are taken and then ranked and success for testing data is measured for training data based on its mean average precision.

Preproccessed data is provided for 1980-2021. Webscraping scripts not needed to run.

Written with Python 3.8

External Libraries used:

NumPy: https://numpy.org/

Pandas: https://pandas.pydata.org/

Selenium: https://selenium-python.readthedocs.io/

BeautifulSoup: https://pypi.org/project/beautifulsoup4/

sklearn: https://scikit-learn.org/stable/
