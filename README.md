# DSC180A-Capstone
![Diagram](diagram.png)

Recording of Quarter 1 Project - https://drive.google.com/file/d/13n6PwG2BHOdqkK5Jao1ja8i5Dx9fGD4R/view?usp=sharing

The producer_test.py file helps produce the tweets and need to be run first. The function_test.py file pre processes the tweets and acts as a middle man between the producer and the consumer topics. Then The tweets are consumed by the consumer_test.py file and ultimely classified by our custom classifier, on a streaming client as the tweets come in.

The /classifier_model folder has the classifier_model_creator.py file which created the logistic regression classifier pickle file. The classifier_model_creator uses training_twitter_data.pkl and twitter_embeddings.pkl file as training data to train the logistic regression model on. 

#### Make sure to replace 
