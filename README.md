# Twitter-Airline-Sentiment-Analysis
2018 Cph University

Sentiment analysis for twitter airline 2015 dataset
### Basic info
14848 Tweets - 10000 train, 2424 validation, 2424 test?

Need to do some basic data exploration. 


### Steps
* Data Exploration - How many words/lemmas? better to use words or lemmas with pos tags?
* Based on that we can find out how much space the word embeddings would take up and how best to analyze

Predicting sentiment - positive negative and neutral.
Find out what 

### Embeddings to try
* FastText - very quick to train, and did well on imdb?
* Feed various lexicons (word->sentiment mappers) into ML methods
* Glove - Twitter, Common Crawl, 
* Word2Vec - Google News
* Twitter



### Machine learning algos to test
* Sentiment neuron from Open AI
* Adversarial - did well on imdb
* Simple self-made LSTM from word embeddings
* Naive Bayes Support Vector Machines (supposed to be good for this)
* Backwards LSTM?






### Links
* Open AI unsupervised sentiment neuron: https://blog.openai.com/unsupervised-sentiment-neuron/
* Comparison of current methods for sentiment analysis: https://blog.paralleldots.com/data-science/breakthrough-research-papers-and-models-for-sentiment-analysis/
* (Did very well on IMDB sentiment) Adversarial training methods for semi-supervised https://arxiv.org/pdf/1605.07725.pdf
https://github.com/tensorflow/models/tree/master/research/adversarial_text
* Possible Lexicons to use: https://arxiv.org/ftp/arxiv/papers/1711/1711.08609.pdf
* Comparison of different word embeddings to try: https://link.springer.com/content/pdf/10.1007/978-3-319-59569-6_42.pdf



