# Predict Churn Rates for a Spotify/Pandora type service

## Installation
You need Anaconda's distribution of Python to run this. The version of Python I've used is 3.

## Project Motivation
Predicting churn rates is a challenging and common problem that data scientists and analysts regularly encounter in any customer-facing business. I built the model using Spark, as it has the ability to efficiently manipulate large datasets.

## File Descriptions
- Sparkify.ipynb - A Jupyter Notebook which has all the code and analysis.
- mini_sparkify_event_data.json - Data on which the analysis is run

## Results

### Metrics
I used the created model on the test set to transform it. The transformed dataset gave me a new column: 'prediction'. I then compared this column with 'label' — the actual values. I calculated how many predicted values were equal to label values (correct predictions), then divided that by the total number of rows, multiplied it by 100 and it gave me the accuracy of the model.

### Accuracy
The accuracy that I got on the testing data is 77%. This is a pretty good estimation and proves my point, the more engaged a user is on a music streaming service, the less likely they’re about to leave it.

Accompanying blog post with detailed analysis: https://medium.com/@rameez.shah/which-users-are-more-bound-to-leave-music-streaming-services-865e872f4bc?postPublishedType=repub

## Acknowledgements
Data is taken from Udacity's Data Science Nano Degree Program's Capstone Project.
