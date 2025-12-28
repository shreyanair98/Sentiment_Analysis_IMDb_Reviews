Using an IMDb reviews dataset, 2 classification models - logistic regression and Naive Bayes - were built to classify positive vs negative reviews.

First, the data had to be cleaned with text standardization practices and tokenization. Then, using TF-IDF vectorization, we prepared the data to be trained/fitted on the 2 specified models.

The data was split into a training and testing sets (with 20% reserved for testing), and the models were run and evaluated using accuracy, precision, recall, and F1-score metrics.

The classifications were also visualized to see which words were more likely to be considered negative vs positive for both models. 
