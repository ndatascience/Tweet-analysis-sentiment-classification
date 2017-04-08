


# Tweet Analysis and Sentiment Classfication

This project focusses on analysing the tweets of John Siracusa -Programmer, tech writer, and co-host of Accidental Tech Podcast. The data is available in .json format(around 3000 tweets - 5 months of tweet data) 

Goals:
- Tweets Analysis
- Sentiment Classification of tweets (postive or negative) using stanford large movie dataset



# Installation

### Download the data
- Clone this repo to your computer
- Get into the folder using cd Tweet analysis-sentiment classification.[working folder]
- The new_siracusa_tweets.json file is in the data folder. 
- Also download the stanford large movie dataset http://ai.stanford.edu/~amaas/data/sentiment/ and put in your working folder.
    - A folder named aclImdb containing train and text folder will be dowloaded.   


### Install the requirements
- Install the requirements using pip install -r requirements.txt
    - Make sure you use Python 2.7.
- Install ggplot
    -pip install git+https://github.com/yhat/ggplot.git

### Usage
- Run the Tweet analysis- sentiment classification.ipynb go through the following steps:
    - Tweet analysis over a period of 2014-02-10 to 2014-06-09 for John Siracusa.
        - Number of Original Tweets and number of retweets    
        - Most frequent hash-tag and co-occuring matrix  
    - Sentiment Classification of tweets using Stanford movie dataset
        - TF - IDF Model
        - Comparison of Classification models - Naive Bayes, Logistic Regression and RandomForest
            - ROC curve
            - Accuracy score
            - Predict and train times        
    - Classify tweets with positive or negative sentiment     
    - Topic modeling using LDA (genism library)
    - Conclusion 

```python

```


```python

```
