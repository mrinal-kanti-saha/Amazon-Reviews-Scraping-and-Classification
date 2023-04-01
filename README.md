# Amazon-Reviews-Scraping-and-Classification
Here, I scraped reviews from a product page under [Amazon](www.amazon.co.in) and used those reviews to train the basic Machine Learning classification models, to learn to classify the reviews as positive or negative.
The ML models used were Logistic Regression, Naive Bayes, K Nearest Neighbour, Decision Trees and Suppport Vector Machines.

## File Contents
The repository consists of two files:- 
1. [Amazon_Review_Scraper](https://github.com/mrinal-kanti-saha/Amazon-Reviews-Scraping-and-Classification/blob/main/Amazon_Reviews_Scraper.ipynb) - This jupyter notebook contain the scraping code.
2. [Boat_Bassheads_100_Review](https://github.com/mrinal-kanti-saha/Amazon-Reviews-Scraping-and-Classification/blob/main/Boat_Bassheads_100_Review.ipynb) - This notebook conatins all the other stuff from basic data cleaning, text data processing, word embedding, and modelling

## Key Learnings
- Scraped reviews for any amazon product using Beautiful Soup 4.
- Cleaned the raw data using standard NLP techniques. 
- Built a dataset out of all the info collected.
- Trained classification models that takes in review content and determines whether the review is positive or negative.
