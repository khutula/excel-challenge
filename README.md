# excel-challenge
GT Bootcamp Excel Homework: Kickstart My Chart


Base Analysis
1. Using only the provided data, we can conclude that:

    a.  The music category is disproportionately more likely to experience a successful campaign (77% vs the population’s 53%).

    b. Within the music category, each sub-category has greater than 87% success rate with the exception of faith, jazz, and world music, which all have 0% success rates.
    
    c. Campaigns initiated in February, April, and May are more likely to experience a successful campaign as well (roughly 60% each vs the population’s 53%).

2. The dataset is only a sample of roughly 4,000 projects and the total population of projects on Kickstarter exceeds 300,000. There could be bias inherent in the way these 4,000 projects were selected for analysis, so the sample may not be properly representative of the whole. More specifically, the overall success rate of our selected projects is over 53%, whereas the success rate in the problem statement is estimated around 33%. This demonstrates the potential bias in the dataset sample selected. Additionally, the majority of this data is collected from 2014 to 2016. Shifts in political and social landscapes over the last five years could mean that success rates by category and sub-category have significantly changed. We may not have current enough data to extrapolate conclusions into today’s landscape.

3. Another table we could analyze would be the count of each project state with one column where staff pick is true and the other is false. How does staff pick influence the outcome of the project? We could also use a scatter plot to graph Goal vs Percent Funded and analyze underlying trends. Could we set our Kickstarter goal lower than our “actual goal” and still get all the funds we need?


Bonus Analysis

In this case, for both the successful and unsuccessful campaigns, the median is a more meaningful summarization of the data than the mean. The mean is extremely susceptible to significant outliers in either direction. Given the significant difference in these values, particularly for the successful campaigns, we can tell that the large number of backers outliers caused a deceptive shift upwards in the mean value.

There is significantly more variation in the number of backers for successful campaigns than for unsuccessful campaigns, as indicated by the higher variance and standard deviation values. This makes sense because, as a general rule, successful campaigns are going to tend to have higher numbers of backers (as represented by the higher maximum, median, and mean values) and this data set even includes a successful campaign that was only backed by one person (as represented by the minimum). Because successful campaigns have a higher range (26456 versus 1293), the variation in the data is bound to be higher.