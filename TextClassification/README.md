# Text Classification
Text classification is the task of assigning a label to some bit of text. Here
 we start you off with a basic example:
 
- [**Sentiment Classifier**](https://colab.research.google.com/github/skafos/colab-example-models/blob/master/TextClassification/sentiment_classifier.ipynb):
  Trains a model to classify user text as positive (5), negative (1), or in between.
- [**Spam or Ham**](https://colab.research.google.com/github/skafos/colab-example-models/blob/master/TextClassification/spam_or_ham.ipynb):
 Trains a model to classify user text as "spam" (bad) or "ham" (good).
- [**Topic Classifier**](https://colab.research.google.com/github/skafos/colab-example-models/blob/master/TextClassification/topic_classifier.ipynb):
 Trains a model to classify user text into one of 20 different topics.
 
## Tips and "Gotchas"
 -  **Common Text Classification Tasks**:
     -  ***Sentiment Classification***: How positive or negative is a piece of text? Typically trained with text data 
     representing user reviews and respective ratings on a scale 1-5. The starter model in this repo contains a basic 
     sentiment classifier trained on yelp reviews.
    -  ***Spam Classification***: How likely is it that a piece of text is considered "spam" or "ham"? Typically trained with 
    text data paired with the appropriate label (spam or ham). The starter model in this repo contains a basic spam classifier
    trained on SMS text message data.
    -  ***Topic Identification***: What is the topic or subject matter of a piece of text? Typically trained with text 
    data paired with related categories. The starter model in this repo contains a basic topic classifier trained on
    news articles labeled with corresponding category (provided by scikit-learn package). 
- **Wrangling Text w/ Turi Create**: Text comes in a host of different formats. Fortunately, the Turi Create text 
classifier handles all [tokenization](https://nlp.stanford.edu/IR-book/html/htmledition/tokenization-1.html), 
and text feature engineering, and cleaning of your text data automatically.


## Need Help?
Didn't find something you need? Confused by something? Need more guidance?

- [**Check out our platform documentation**](https://docs.skafos.ai)

Please contact us with questions or feedback! Here are two ways:

-  [**Signup for our Slack Channel**](https://join.slack.com/t/metismachine-skafos/shared_invite/enQtNTAxMzEwOTk2NzA5LThjMmMyY2JkNTkwNDQ1YjgyYjFiY2MyMjRkMzYyM2E4MjUxNTJmYmQyODVhZWM2MjQwMjE5ZGM1Y2YwN2M5ODI)
-  [**Find us on Reddit**](https://reddit.com/r/skafos)

Also checkout Turi Create's [**documentation**](https://apple.github.io/turicreate/docs/userguide/text_classifier/) on
 text classification basics.
 
