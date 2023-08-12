
# Reviews Sentimental Analysis

## Inroduction 

Every day, we encounter many different things to buy, especially online where we see lots of options in one category. Choosing can be hard. That's where 'reviews' come in. People who already bought a product give it a rating and write about their experience. Ratings help us quickly decide if something is good or bad. But for detailed reviews, we have to read everything to know if it's positive or negative. Nowadays, technology like Natural Language Processing (NLP) in artificial intelligence makes this easier.





## Sentimental Analysis

Sentiment Analysis is the most common text classification tool that analyses an incoming message and tells whether the underlying sentiment is positive, negative our neutral.Understanding people’s emotions is essential for businesses since customers are able to express their thoughts and feelings more openly than ever before.It is quite hard for a human to go through each single line and identify the emotion being the user experience.Now with technology, we can automatically analyzing customer feedback, from survey responses to social media conversations, brands are able to listen attentively to their customers, and tailor products and services to meet their needs.
## Objective 

1)Reviews Preprocessing and Cleaning

2)Story Generation and Visualization from reviews

3)Extracting Features from Cleaned reviews

4)Model Building: Sentiment Analysis


## Dataset :

https://www.kaggle.com/datasets/eswarchandt/amazon-music-reviews/download?datasetVersionNumber=2
## Dataset Description

This file has reviewer ID , User ID, Reviewer Name, Reviewer text, helpful, Summary(obtained from Reviewer text),Overall Rating on a scale 5, Review time

Description of columns in the file:

1)Reviewer ID: The unique identification of the person who wrote the review, like A2SUAM1J3GNN3B.

2)Product ID: The unique identification of the product being reviewed, such as 0000013714.

3)Reviewer Name: The name of the person who wrote the review.
Helpful: A rating indicating how helpful the review is, often shown as a fraction like 2/3.

4)Review Text: The actual text of the review.

5)Overall Rating: A rating given to the product, usually on a scale from 1 to 5.

6)Summary: A brief summary of the review.

7)Unix Review Time: The time the review was posted, in Unix time format.

8)Review Time: The time the review was posted in its raw form.
## Project Flow

Loading Packages and Data

Data Structure and Content

Missing Value Treatment

Exploratory Data Analysis

Feature Engineering

PreProcessing Data
  
    Label Encoding and 
    Standardization

Modeling
   
    1) Logistic Regression
    2)Random Forest Classifier
    3)Bernoulli-NB
    4)KNeighborsClassifier
    5)Support Vector Classifier(SVC)
    
## 🚀 About Me


I'm a Data Science enthusiast and on a quest to explore, analyze, and derive insights from data. Curious learner, avid participant in competitions, and dedicated to contributing to the data science community. Let's embark on this exciting data-driven journey together!