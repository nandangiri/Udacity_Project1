# Seattle's Aribnb Listing Analysis


### Contents

1. [The Libraries That I Have Used](#libraries)
2. [My Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)

## Libraries

The project was implemented using Anaconda distribution of Python 3.0. Moreover I have used the following python libraries:

1. Collections
2. Matplotlib 
3. NLTK
4. NumPy
5. Pandas
6. Seaborn
7. Sklearn

## Motivation

The Seattle's Airbnb seems to be an intrihuing dataset. So, from a learning standpoint and from an exploration standpoint, we explore that dataset.

We classify our questions into 3 categories, viz. Pricing Trends, Sentiment Analysis and Price Prediction. Each of these categories have a group of questions from the below. Some questions to think of are...

1. How does the pricing increase or decrease by season?
2. What is the peak season in Seattle?
3. How does the pricing increase or decrease by neighborhood?
4. Which ones are the priciest neighborhoods in Seattle?
5. How does property types within neighborhoods impact price for the most expensive neighborhoods and most common property types?
6. How can we categorize reviews based on sentiments?
7. Can we map positive and negative sentiments from reviews to neighborhoods to understand which neighborhoonds rank higher on the positive sentiment scale and which ones rank higher on the negative sentiment scale?
8. Can we explore some of the worst reviews for additional insights?
9. Can we predict a price for a given listing?
10. What factors of the listing correlate best for predicting the price?


## File Descriptions

- Jupyter notebook
- HTML version of the Jupyter notebook
- Datasets used (compressed since the file size is large)
- Readme.md
- Medium Blog


## Results

Some of the key findings are as below.

1. The peak season in Seattle is during the summer months from June to August, with its peak in July. 
2. The "Southeast Magnolia" neighborhood seems to be  costilest neighborhood in Seattle, followed by Portage Bay. Rainier Beach is the least pricy.
3. The houses in Portage Bay are costliest seconded by West Queen Anne and Westlake. 
4. Using sentiment analysis, we observe that 97.2% of reviews were mostly positive, 1.8% were neutral and 1% were negative
5. Roxhill, Cedar Park and Pinehurst ares have the better or positive reviews
6. University District, Holly Park and View Ridge has a slightly negative reviews
7. We implement LinearRegression to predict price based on a prepped and cleaned dataset, with an r^2 score of 0.62 on both training and test datasets.
