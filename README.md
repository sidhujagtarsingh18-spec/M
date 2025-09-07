# M
This project demonstrates how AI can classify text as **Positive**, **Negative**, **Neutral** using Natural Language Processing (NLP) techniques.
  Sentiment Analysis Project
This repository is created as a part of the "Grow with Google - Learn Basics of AI" course.
It demonstrates a simple Artificial Intelligence project using text sentiment analysis.

"##SUMMARY"

## 1. Name and Description
"Project Name" - Sentiment Analysis on Text 
"Description:" - This project analyses short text ( like reviews or comments) and predicts whether the sentiment is "positive" or "negative".ound
Artificial Intelligence is widely used in understanding human language . Companies like Amazon, Netflix, and Google use sentiment analysis to know what users feel about their products or services.
This project is a very simple version of that . 
-------------

## 3. Data and Ai techniques
- "Data":- A small set of example sentences (e.g., "I love this movie"- Positive ,  " I hate waiting" - Negative" )
- "AI Technique:" - Rule based text classification (using simple keywords like "good, happy, love, hate, bad ").
  > Since this is a beginner project, we are not using big machine learning models for datasets.
--------------

##4. How it is used 
-user enters a sentence  (e.g.,  *” The food was great”*).
- The program checks for positive or negative words.
- It outputs whether the sentiment is **Postive ** or ** Negative**.

- # Simple Sentiment Analysis Program for AI Course Project


def analysis_sentiment(text):
    postive_words = ["good","great","happy","love","excellent"]
    
    negative-words = ["bad","terrible", "sad","hate","angry"]


    text = text.lower( )
    score = 0
    

    for word in positive_words:
       if word in text:
	score += 1

    for word in negative_words:
      if word in text:
      score -= 1

  

     if score > 0:
      return "Positive"
     
     elif score< 0:
      return "Negative"

     else:
     return "Neutral"  

-------------------

## 5.  Challenges or Limitations
-	Only works with small, simple sentences.
-	Cannot handle sarcasm or complex text.
-	Uses basic keyword matching (not advanced ML or Deep learning.)
------------

##6. What  next
-	Use a large dataset of reviews or  tweets.
-	Train a machine learning model ( like Naïve Bays or Logistic Regresssion).
-	Improve accuracy with Natural Language Processing (NLP) techniques.

--------------
##7. Acknowledgement
This project was created for the  ** Grow with Google- Learn Basics of AI Course**.
Special thanks to the course instructors and resources that guided this learning journey.
--------------

