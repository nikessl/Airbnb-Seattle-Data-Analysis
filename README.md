# Airbnb Seattle Data Analysis
 
### Install

**Python 3.x** is required to run this project and the following Python libraries have to be installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)

Furthermore a software has to be installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html) 
I use [Anaconda](https://www.continuum.io/downloads) to do so.

### Project Motivation
This project is part of the Data Science Nanodegree I am doing at Udacity. I chose the dataset "Seattle Airbnb Open Data" as part of a submission to apply the concepts I learned. The aim of the small analysis was to find out which aspects lead to high and low prices for appartments in Seattle.

### Files 
Included is the code that I wrote in python `Data Analysis.ipynb`, and the `README.md` file, that you are reading right now.

### Data
The data used in this analysis is real Airbnb data public available on [kaggle.com](https://www.kaggle.com/airbnb/seattle)

### Run
You can run the code by downloading it from this repository, opening it in your notebook. In order to run the code you will need to download the data from [kaggle.com](https://www.kaggle.com/airbnb/seattle) and save it into the same folder, the code file is in. You can then just simply run the code.

### Questions

The questions addressed in this analysis are:
1. In which season do prices in Seattle climax?
2. Which areas of the city are most affected by the price spike?
3. Which attributes are the most important to predict prices?

### Results
The main results of the analysis are:
1. Prices for Airbnb apartments are most expensive in the summer months (June, July & August)
2. The area that is mostly affected by the seasonal effect on prices is Downtown Seattle, while all of the areas are more expensive over summer
3. The location of an apartment is the most important aspect for its price
4. The fact that an apartment is a "Loft" has the highest impact on prices in the category "property style"
5. The more bedrooms, bathrooms and number of accommodates an apartment has the more expensive it is
