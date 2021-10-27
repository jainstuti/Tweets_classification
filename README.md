# Tweets_classification

The dataset consisted of 163K records which was difficult to process in google colab, so I have made predictions for each model in separate notebook. Also, it was taking a lot of time to process such a large dataset therefore, I have only taken some thousand records for each model according to the time it was taking to make predictions in each case. 
According to the predictions made, with only 30K records, ensemble acheived the accuracy of around 78% while the highest accuracy was that of random forest with 90K records. Also, I started with 10K records in each model and with increasing number of records, accuracy was increasing. This implies, all the models would perform better if trained on more records. Going with the trend of increase in accuracy with increase in number of records used to train the models, ensemble is performing best for the given problem statement. Not only going by trend, accuracy of ensemble as compared to that of random forest is higher when both were trained on 30K records.
The decreasing order of performance of the models is:
ensemble > random forest > decision tree > naive bayes > k-nearest neighbours.
