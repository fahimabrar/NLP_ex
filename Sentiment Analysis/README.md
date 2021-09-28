# Sentiment-analysis
Sentiment is how much emotion a sentence contains

There are two types of methods for sentiment analysis in Natural Language Processing domain

- Rules based methods
- Machine learnable methods

## Rule based Sentiment Analysis
In rules based methods sentiment score is hand crafted by humans. A certain value for sentiment for words is assigned by human.

Libraries 

### Textblob

Textblob is a library that can find sentiment in sentences based on predefined scores for sentiment containing words. 

e.g. TextBlob("good").sentiment
ouput : Output: Sentiment(polarity=0.7, subjectivity=0.6000000000000001)

- Here Polarity means how much positive or negative meaning the text has. e:g: good is positive word and bad is a negative word. Polarity scaled between -1 to +1.

- -1 means the extremely negative meaningful text. +1 means the most positive text.

- Subjectivity means how much subjective the text is. e:g: how much opinion, emotion expressed in the text. Subjectivity scaled between 0 and +1.


### VEDAR

Vedar can find sentiment in four scales. Positivity, Negativity, Neutral and Compound. This scales itself are self explanatory. The score is between 0 to 1. VEDAR can also find sentiment in emoticons. A happy face will get positivity score close to 1 and Negative face will get negative score close to 1. 


## Machine Learnable Sentiment Analysis
to be continued
