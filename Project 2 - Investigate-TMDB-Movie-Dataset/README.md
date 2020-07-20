# Investigating TMDB Movie Dataset
This dataset comes from IMDB and contains information about 10,000 movies,
short films and tv series collected from The Movie Database (TMDb), including user
ratings, revenue, runtime and budget.

## Introduction:
The primary goal of the project is to go through the general data analysis process — using basic data analysis technique with NumPy, pandas, and Matplotlib.

### Database Schema:

This data set contains information about 10,000 movies collected from The Movie Database (TMDb). Contains data such as `title, cast, director, runtime, budget, revenue, release year` etc. 
- Certain columns, like `‘cast’` and `‘genres’`, contain multiple values separated by pipe (|) characters.
- There are some odd characters in the `‘cast’` column. Nothing to care much of, I leave them as is.
- The final two columns ending with `“_adj"` show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

## Prerequisites

You need to install the following libraries


* pandas 
* numpy 
* statsmodel.api 

This project requires **Python 3** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Matplotlib](http://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/installing.html)
- [Statsmodel](https://www.statsmodels.org/stable/index.html)


### Installing

Run the following commands on command prompt.


```
pip install pandas
pip install numpy
pip install statsmodel
```
