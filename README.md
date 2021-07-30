# Text Classification on Amazon Customer Reviews Dataset

Establish a rate prediction model based on customer reviews using NLP techniques in order to show more consistent and helpful comments to customers in most appropriate order.

## Motivation: 

Nowadays, the spread of e-commerce and the increase in product diversity have created a need for customers to choose the right and most suitable product. Therefore, when customers want to choose the most suitable product for themselves and their budget, the reviews of other customers about their experiences with that product have become more valuable. For this reason, it is possible to say that customer reviews provide an objective feedback to the customer who will buy the product in his purchasing process. 
While customers make comments about the product, they also make different types of ratings to summarize their reviews about the product. These ratings can be identified by the number of stars or a different numerical rating types. These summary ratings may vary depending on the customer's character, mood or personal differences of opinion and sometimes do not fully reflect the experience of the product. At this point, the main thing that reflects the relevant feedback is actually the customer review text itself. In this context, the main purpose of this project is to analyze the reviews made by customers using NLP techniques and try to predict the most accurate rating based on the meaning of the text.


## Dataset

Customer reviews collected from the Amazon e-commerce website are aggregated from all reviews by each customer, with each customer review representing an integer ranging from one star to five stars. Customer reviews collected from the Amazon e-commerce website are aggregated from all reviews by each customer, with each customer review representing an integer ranging from one star to five stars. Therefore, we will need a supervised and multiclass classifier in this study. Besides, we will try to perform feature extraction to apply the best machine learning algorithm to solve our classification problem using Natural Language Processing (NLP) techniques like word embedding, topic modeling, and dimension reduction etc. <br>

The entire dataset collected from Amazon contains product reviews and metadata, including 233.1 million reviews spanning May 1996 - Oct 2018. There are 29 categories in total, but the category "All beauty" was chosen within the scope of this study. It contains a total of 371,345 customer reviews and has 12 features. These fetaures and their explanations are briefly as follows: 

[Click to See Entire Dataset](http://deepyeti.ucsd.edu/jianmo/amazon/)

* **reviewerID** - ID of the reviewer
* **asin** - ID of the product
* **reviewerName** - name of the reviewer
* **vote** - helpful votes of the review
* **style** - a disctionary of the product metadata
* **reviewText** - text of the review
* **overall** - rating of the product
* **summary** - summary of the review
* **unixReviewTime** - time of the review (unix time)
* **reviewTime** - time of the review (raw)
* **image** - images that users post after they have received the product
* **verified** - information whether the customer who made the review purchased the product or not

## Necessary Libraries

* NLTK
* Gensim
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Sklearn
* Tensorflow

## Versions

**Gensim:** 3.8.3
**NLTK:** 3.5

## NLP Techniques Used

* Bag of Words
* TF-IDF
* Word Embedding
* LDA
* Topic Modelling

## ML & DL Algorithms

* Random Forest
* Decision Tree
* Extra Tree Classifier
* XGBoost
* LSTM
* LSTM + CNN

[For More Detail, Please Go My Capstone Project Presentation or Report](https://github.com/forxinecesimsek/text_classification/blob/dd208edcf303ba77c62b5e5ce97319dc589db8af/Text%20Classification%20-%20Capstone%20Project%20Report.pdf)
