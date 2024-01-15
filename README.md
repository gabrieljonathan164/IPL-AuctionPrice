# STUDY OF SOCIAL MEDIA PRESENCE INFLUENCING IPL PLAYER AUCTION PRICES 

The Indian Premier League (IPL) is a very well-known T20 cricket league that draws the best players from all over the world. The IPL's player auctions, where franchise owners bid for players based on their prior performances, are one of its defining characteristics. The question for research is whether, in addition to past performance, other factors, such as age, captaincy abilities, fan following, etc., affect a player's auction price.

The IPL has a huge global fan base and is a multi-billion-dollar industry. The success of the teams depends on the player auctions, and the team's performance can be impacted by overpaying or underpaying players. To maximize their chances of winning the tournament and make better decisions, franchise owners must therefore understand the factors that influence the players' auction price.

Additionally, in addition to a player's on-field performance, other factors that affect the auction price include their off-field persona, including their social media presence, fan base, and leadership abilities. Teams can enhance their marketing plans and entice more league sponsors by researching how these variables affect the players' auction prices.

DATA & METHODOLOGY: 
 
I gathered information from a variety of sources, including Kaggle and the official IPL website, to address the research problem. The dataset includes data on a player's statistics, including their total auction price, batting points, and bowling points for the years 2020 – 2022. I manually gathered additional data from search engines and social media applications to examine the effects of other variables like age and social media use. 
 
Because it includes various variables pertaining to the players' past performance, social media presence, and age, the nature of the data is appropriate to address the research problem. The fact that the data is in the form of a structured dataset makes statistical analysis of it simple. 
 
Data cleaning, preprocessing, and exploratory data analysis were just a few of the steps taken in the methodology used to get the data ready. To ensure data accuracy, the first step was to eliminate any missing or duplicate values from the dataset. To ensure that all variables were on the same scale and to prevent the model from being biased towards any variable, I then performed data preprocessing, which included feature scaling and normalization. 
 
I investigated the connection between the variables and the players' auction price during the exploratory data analysis stage. To find any patterns or trends in the data, I used a variety of visualization techniques, such as scatter plots, bar plots, and histograms. 
 
Finally, I investigated the relationship between the variables and the players' auction price using linear regression analysis. The most significant factors that had the greatest influence on the auction price were also found using feature selection techniques. 

VISUAL FINDINGS - BATSMEN

1. Linear Regression for Batsmen with all variables vs Linear Regression for Batsmen Excluding social media variables.
![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/1.1.png)    ![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/1.2.png)

2. Linear Regression for Batsmen excluding Age and Linear Regression for Batsmen excluding Player of the match.
![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/2.1.png)    ![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/2.2.png)

3. Finding Hitters based on Boundaries per Balls faced metric.
![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/3.png)

4. Finding Top Runners based on Total runs.
![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/4.png)

VISUAL FINDINGS - BOWLERS
1. Linear Regression for Bowlers with all variables vs Linear Regression for Bowlers excluding social media variables.
![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/5.1.png)    ![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/5.2.png)

2. Linear Regression for Bowlers excluding Age and Linear Regression for Bowlers excluding Player of the match.
![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/6.1.png)    ![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/6.2.png)

3. Finding Wicket takers based on Wickets taken.
![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/7.png)

4. Finding Top Bowlers with low Average Economy.
![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/8.png)

CONCLUSION

The research done on the effects of social media activity, player of the match, and age on IPL player auction prices is both fascinating and insightful. The results from Figures 1, 2, 7, and 8 show that while there was a moderate correlation between social media presence and auction price, this factor has little impact on a player's anticipated auction price. Similar findings can be drawn from Figures 3, 4, 9, and 10, which indicate that neither player of the match nor age appear to significantly affect the IPL player auction price. These intriguing findings provide new insight into the selection criteria used by IPL team owners during player auctions and raise the possibility that other considerations may have a greater impact on a player's price tag. 

 

Our analysis' conclusions have important ramifications for IPL team owners and their player recruitment plans. Team owners can identify high-performing players who are currently being paid less than their market value by using Figures 5, 6, 11, and 12. This knowledge can be applied to improve a team's lineup for bowling or batting, which could result in improved performance and increased success in the league. Additionally, team owners can use this information to retain the services of these players by providing them with better contracts and ensuring that they are still a part of the team's long-term goals. To increase their chances of taking home the coveted IPL trophy, teams that don't currently have these players on their roster can target them in the upcoming auction. Overall, our study offers insightful information about IPL teams' player acquisition strategies, which is advantageous to both teams and players. 

 

However, it is important to note the analysis was performed on a small dataset, and there may be other variables not considered in this analysis that could significantly impact the player's auction price. The analysis also did not consider the team's requirements and budget constraints, which may play a significant role in determining a player's auction price. 


Here are a few snippets of the Tableau Stories - Please download to view the actual story and review the findings - https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Final%20Batsmen%20IPL.twbx | https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Final%20Bowlers%20IPL.twbx
Snippet 1: ![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/Story1.png)

Snippet 2: ![alt text](https://github.com/gabrieljonathan164/IPL-AuctionPrice/blob/main/Images/Story2.png)
