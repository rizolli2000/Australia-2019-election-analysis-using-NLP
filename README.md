# Australia-2019-election-analysis-using-NLP


Introduction:
The purpose of this report is to present the analysis of tweets related to the Australian Election 2019. The analysis involves predicting the sentiment of the tweets and determining the favorite candidate based on the tweets. The analysis incorporates both web scraping using the Tweepy library and the use of a CSV file containing tweet data. The Natural Language Toolkit (NLTK) library is used for text preprocessing and sentiment analysis. The accuracy achieved in sentiment prediction is 71 percent.

Data Collection:
To collect the tweet data, two methods were used:
a. Web Scraping using Tweepy: The Tweepy library was utilized to access Twitter's API and scrape tweets related to the Australian Election 2019. The collected tweets were stored for further analysis.
b. CSV File: In addition to web scraping, a CSV file containing tweet data related to the Australian Election 2019 was used. This file may have been collected previously or obtained from a third-party source.

Preprocessing and Sentiment Analysis:
The collected tweet data underwent preprocessing steps using the NLTK library:
a. Text Cleaning: The tweets were cleaned by removing URLs, special characters, and numbers, leaving only the textual content.
b. Tokenization: The tweets were split into individual words or tokens.
c. Lemmatization: The tokens were lemmatized to reduce them to their base form, ensuring uniformity in the dataset.
d. Sentiment Analysis: The NLTK library was used to determine the sentiment of each tweet, classifying them as positive, negative, or neutral.

Sentiment Prediction Accuracy:
The sentiment analysis model built using the NLTK library achieved an accuracy of 71 percent in predicting the sentiment of the tweets. This accuracy was determined by comparing the predicted sentiment labels with the ground truth sentiment labels available in the dataset or through manual annotation.

Determining Favorite Candidate:
To determine the favorite candidate based on the tweets, various factors can be considered:
a. Sentiment Distribution: Analyzing the sentiment distribution of tweets mentioning each candidate can provide insights into the overall sentiment towards them. The candidate with the highest proportion of positive sentiments may be considered the favorite.
b. Frequency Analysis: Conducting frequency analysis on the tweet mentions of each candidate can reveal which candidate was discussed the most. The candidate with the highest frequency of mentions may be perceived as the favorite.

Recommendations:
Based on the analysis of Australian Election 2019 tweets, the following recommendations can be made for political parties and policymakers:
a. Monitor Social Media: Continuous monitoring of social media, especially during election periods, can provide real-time insights into public opinion and sentiment towards political events and candidates.
b. Engage with Voters: Engage with voters on social media platforms by actively participating in discussions, addressing concerns, and sharing policy updates. This can help build a positive image and connect with the electorate.
c. Tailor Campaign Strategies: Utilize the insights gained from sentiment analysis and frequency analysis to tailor campaign strategies and messaging to resonate with the public sentiment and priorities.

Conclusion:
The analysis of Australian Election 2019 tweets using web scraping and a CSV file, along with sentiment analysis, provides valuable insights into public opinion and sentiment towards the election and candidates. The accuracy achieved in sentiment prediction is 71 percent. By leveraging social media insights, political parties and policymakers can refine their strategies and engage with voters more effectively.
