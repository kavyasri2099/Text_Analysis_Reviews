# Text_Analysis_Reviews  
  
`Project Overview`  

This project aims to analyze and classify Amazon product reviews. The goal is to preprocess the text data, extract meaningful features, and build machine learning models to predict the review scores.  

`Dataset`  

The dataset is extracted from a zip file containing multiple text files of Amazon reviews. Each file contains the following information:  

`ProductId`: The ID of the product.  
`UserId`: The ID of the user who wrote the review.  
`ProfileName`: The profile name of the user.  
`HelpfulnessNumerator`: The number of users who found the review helpful.  
`HelpfulnessDenominator`: The total number of users who evaluated the review.  
`Score`: The rating given by the user (1-5).  
`Time`: The time when the review was written (in UNIX timestamp).  
`ReviewSummary`: A brief summary of the review.  
`ReviewText`: The full text of the review.  
  
`Project Structure`  
  
`txt_reviews.zip`: The zip file containing the text reviews.(I Have uploaded the Sample Files)  
`Text_project_Main.ipynb`: The Jupyter notebook containing the code for data extraction, preprocessing, and model training.  
`sample_text_data_flat.csv`: A sample dataset of preprocessed review texts and features.(I Have uploaded the Sample CSV File)  
  
`Key Steps`  
  
`Data Extraction and Loading`:  
  
-- Extract reviews from the zip file.  
-- Load the reviews into a pandas DataFrame.  
  
`Data Preprocessing`:  
  
-- Calculate helpfulness scores.  
-- Convert review times to a readable format.  
-- Clean and tokenize the review texts.  
-- Remove stopwords and lemmatize tokens.  
-- Create a lemmatized text column for further analysis.  
  
`Exploratory Data Analysis (EDA)`:  
  
-- Plot the distribution of review scores.  
-- Plot the distribution of helpfulness scores. etc.,  
  
`Text Vectorization`:  
  
-- Use TF-IDF vectorization to convert text data into numerical features.  
  
`Model Training and Evaluation`:  
  
Logistic Regression  
Multinomial Naive Bayes  
Gradient Boosting  
Support Vector Machine (SVM)  
Random Forest  
Compare models based on accuracy.  
  
`Results`  
  
Logistic Regression Model: Accuracy: 71.59%  
Multinomial Naive Bayes Model: Accuracy: 65.74%  
Gradient Boosting Model: Accuracy: 67.55%  
Support Vector Machine Model: Accuracy: 71.53%  
Random Forest Model: Accuracy: 70.23%  
The Logistic Regression model achieved the highest accuracy in predicting the review scores.  
