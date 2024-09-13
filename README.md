# Sentiment Analysis on IMDB Dataset of Movie Reviews (LSTM)

## Overview

This project mainly focusing on creating a LSTM Prediction Model to predict the review either is it  positve or negitve based on the review data .The IMDB dataset is a collection of 50,000 movie reviews from IMDB, 
labeled as either positive or negative. This dataset is often used for sentiment analysis.

## Steps follwed in the Project  

1. Importing the dataset from the kaggle and importing the necessary libraries.

2. Craeating the directiory for the json.

3. Extracted the files from the downloaded dataset file.

4. Convert the csv file to dataframe using pandas library.

5. Encoded the labeles as 1 and 0 for the output.

6. Checking the distribution of the data(balanced or imbalanced)

7. Spliting the data into test and train data.

8. Data preprocessing ,Tokenizing the data and apply Pad_sequences for arranging into uniform dimensions.

9. Create the LSTM setup for the model creation.

10. Build the model with embedding layers , input and output layers .

11. Compile the model with loss ,optimizers and metrices.

12. Train the model with the training data with required number of Epoches.

13. Evaulate the model with loss and accuracy.

14. Build the Predictive System for the user testing.
