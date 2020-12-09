

 

The Case study contains 3 ipython notebooks and 3 csv files and follwing is the way they are used

1. scraping .ipynb ipython notebook contains the code for scraping the reviews from the amazon website for 10 mobile phones. It uses the phone_list.csv for accessing the websites. 

2. The output is the phone_review.csv file which contains the name of the model, the reviews and start ratings.

3. Training_DistilBERT.ipynb is the training of BERT model on the given data. The code was implemented on kaggle. It trains and saves the weights of the model.

4. testing_the_model.ipynb uses phone_review.csv and the trained weights. Creates a review_score.csv which contains the score predicted by the trained model. 




