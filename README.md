# Berlin-AirBnb-Data

The Berlin AirBnb project aims at exploring the price and rating of airbnb appartments in Berlin. Its purpose is to develop an understanding of the main drivers of a good rating, of the influence of the neighbourhood on price and rating, and of the behaviour of prices across the city and over time.

I have based my analysis on two datasets compiled on November 12th, 2019, and which can be downloaded directly from [this Kaggle folder](http://insideairbnb.com/get-the-data.html) (scroll down to Berlin, Germany):
- listings.csv.gz
- calendar.csv.gz

## Libraries

The data preparation and analysis have been executed in Python 3.7.5.

I used the following libraries to prepare the data and perform the analysis:
- numpy
- pandas
- matplotlib
- sklearn
- keplergl
- operator
- datetime

The two last libraries do not require to be installed independently from Python 3.7.5.

## Files in Repository

- berlin_airbnb_data_analysis.ipynb : this Jupyter Notebook contains the code used to prepare and analyse the data. 
- AirBnbDistrictsMap.html : a Kepler map of Berlin neighbourhoods
- AirBnbRatingsMap.html : a Kepler map of appartment ratings in Berlin

Both maps need to be downloaded, either as part of the entire repository or separately, in order to be opened.

## Summary 

It appears that the neighbourhood in which an appartment is located has a strong influence on its price, but not so much on the rating it receives.

The strongest drivers of a good rating are the seniority of the host on airbnb, and the price of the appartment.

## Detailed Analysis

A blog post stating the major findings of the analysis can be found [here](https://medium.com/@mahaut.segonzac_87677/are-you-a-good-airbnb-host-2697508d8cc5).

## Acknowledgements

I would like to thank my Udacity mentor who helped me find the right angle to approach this dataset.
