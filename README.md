<div id="container" style="position:relative;">
<div style="position:relative; float:left"><img style="height:140px, width:280px" src ="images/covid_cover.png" />
</div>

# Combating Covid-19 Misinformation
  -----------------------------------------------
  
  
## How can we combat Covid-19 misinformation using Natural Language Processing (NLP), Machine Learning, and Statistical Algorithms?
  ----------------------------------------------------------------------------------------------------------------------------------
  
  **This project is still ongoing and will be updated periodically as more data is collected relating to covid-19**
  
  So, how can we combat Covid-19 Misinformation using Natural Language Processing? Can we assist individuals using the internet detect falsehoods they may encounter every day? My aim for this project is to create a NLP Classification Model to detect whether an article, post, and tweet is fact “real” or fiction “fake”.
  
## Related Work
  
  Covid-19 Misinformation is just the tip of the iceberg when dealing with ‘Misinformation’. Data Science I believe is the best tool if not the only tool to combat falsehoods on a large scale. Not only when dealing with text information i.e., News Articles, Tweets, and Posts, but including Audio, Photo, and Video files that are emerging today as “Deep Fakes”. These types of problems can quickly go viral and have tremendous consequences on health, public opinion, and or cause financial damage to its victims.
  
## Data Construction
  
  The data used for this project was acquired from the CoAID Dataset [1] which is separated into true data frames and fake data frames. Additionally, the CoAID Dataset includes Twitter data that is separated into true and fake data frames as well. I then uploaded the individual data sets, labeled each data frame “real” or “fake”, lastly, I merged the corresponding data together to form two separate (Article and Twitter) data frames.
  
  **CoAID Dataset** -
  
@misc {cui2020coaid, 
  title={CoAID: COVID-19 Healthcare Misinformation Dataset}, 
  author={Limeng Cui and Dongwon Lee}, year={2020}, eprint={2006.00885}, 
  archivePrefix={arXiv}, 
  primaryClass={cs.SI} }
  
From <https://github.com/cuilimeng/CoAID/blob/master/README.md>
  
## Text Pre Processing & EDA
  - Tokenization
  - Machine Learning
  - Data Visualization
  - TF-IDF 
  
## Methods
  - SVM (Support Vector Machine) - BOW (bag-of-words) to represent text data, and feed the representations to a linear kernel SVM
  - Logistic Regression - Concatenate all the word embeddings together, and feed it to the model.
  - Random Forest - BOW (bag-of-words) to represent text data, and feed the representations to the model.

## Technologies
  - Jupyter Notebook
  - Python
  - Pandas
 
