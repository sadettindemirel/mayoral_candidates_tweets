Analyzing Mayoral Candidates of Ankara and İzmir
================

This work had been done for Data Journalism Project assignment of Master program in Investigative Journalism at University of Gothenburg. The project focused on the Twitter popularity of mayoral candidates in İstanbul and Ankara for the upcoming local election on March 31th.

**Metholodgy**

* How I calculate the popularity metrics:

Between candidate’s tweets data that we grabbed include number of likes, retweets, published date and the number of followers. We preferred use two different calculations:

**Average Number of Likes (Average Likes)**
→ Average Number of Likes is calculated by taking average of number likes per tweet.

Metrics  = average(number of likes)

**Daily Popularity Score (based on the number of followers)**
→ The second method is devised to make more sophisticated analysis. I calculated the daily popularity score based on followers’ number of candidates, by dividing the number of likes per tweet. In this case the results are fairer than first method, because it measures popularity of candidates by dividing the number of likes into their followers’ number. 

Metrics = (number of likes)/followers count

The data sets that were used in this analysis can be reused by anyone freely. Tweet data was retrived from Twitter REST API by using rtweet package.

**[Click to reach out Detailed analysis](https://sadettindemirel.github.io/mayoral_candidates_tweets/analysis-of-tweets.html)**

