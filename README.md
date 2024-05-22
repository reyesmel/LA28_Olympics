# LA28_Olympics

#### Background
COMM 557 Data Science for Communication and Social Networks<br/>
USC Annenberg School for Communication and Journalism<br/>
USC Viterbi School of Engineering Data Science Program

#### General Note
The files for this project are Jupyter Notebooks that scrape data into json files and after data preprocessing, are saved as csv files. As the code runs more csv files will generate and save in the same folder, aside from the files listed below.<br/>

The files included for this project explores the correlations between topics and sentiment in 500,000+ tweets scraped via Twitter API. Specifically it explores the sentiment towards the LA28 Olympics given that at the time of analysis, many Angelenos and activist groups were turning to Twitter and other social media to express concerns about the event, comparing it to the Super Bowl LVI. Found overall positive sentiment with a significant proportion of neutral responses indicating a notable effect size and uncovered key issues in negative sentiment.<br/>

#### Packages Required
* networkx
* tweepy
* numpy
* matplotlib
* time
* csv
* pandas
* json
* nltk
* spacy
* datetime
* re
* string
* unicodedata
* corpora
* TextBlob
* SentimentIntensityAnalyzer

#### Files Required
* Sentiment Analysis + Clean up.ipynb
* super_olympics.json
* clean_super_bowl_olympics.json
* filtered_super_bowl_olympics_tweets.csv
* official_subjectivity_polarity_scores_super_olympics_tweets.csv
* twitter_research_api_scraping_code.ipynb
* twitter_research_api.json _(not included)_

#### Data Sources 
Scraped tweet data between 4/1/2020 and 4/1/2022 containing keywords associated to the LA28 Olympics, the Super Bowl, and anti-olympics activist group [NOlympicsLA](https://x.com/NOlympicsLA). 

#### Running Code
The twitter_research_api_scraping_code.ipynb file will not run as I have not shared the twitter_research_api.json file with my API Key. The API Key listed in the notebook is just an example.<br/>

The Sentiment Analysis + Clean up.ipynb file will take in the remaining files to clean the data and conduct a sentiment analysis on the clean and filtered data. 
