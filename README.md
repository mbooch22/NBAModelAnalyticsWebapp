
# NBAModelAnayltics
Webapp for displaying NBA Machine Learning Predictive Model vs Vegas odds

Using a proprietary web scraping web app, NBA stats over the past 5 years were retreieved for every game played.

After retreiveing all the data, it was used to train a Machine Learning on AWS Amazon Sagemaker. 

The Model was trained to predict various stats for any game being played for any two teams. 

For any prediction being made, fresh data (at least updated from the last two weeks) from the two teams being played are fetched.

Using this fresh data, the Model then predicts: Winning Percentage (Moneyline), Point Margin (Spread), Home Team Total (Over/Under), Away Team Total (Over/Under), Game Total (Over/Under).

The predictions of the Model are then used against the corresponding Vegas Odds. Various thresholds are used to determine the optimal chances of winning against Vegas. 

This app will be used to display how the Predictive Model is Performing against the Vegas Odds. (Goal = 60 %)

View App <a href="https://mbooch22.github.io/NBAModelAnalyticsWebapp/login.html"><strong>Here</strong></a> Please contact for password to site.


