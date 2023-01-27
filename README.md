# Marketing_Campaign_Performance_Analysis
A Data Analysis/Science project analysing marketing campaign performance with Python

It’s imperative that Marketing Data Analysts and Scientists are able to:

1. Analyse marketing campaign performance against KPIs,
2. Attribute conversions to marketing channels,
3. Understand performance across different audiences using customer segmentation to determine true success or failure to guide future campaigns,
4. Discover campaign implementation errors and quantify the impact on the business.

This project demonstrates all the skills above and below.

## Skills

The skills required to do this project are:

- Domain knowledge: Digital marketing:
    - Know which KPIs measure success,
    - Identify opportunities for Feature Engineering,
    - The importance of customer segmentation,
    - Identify inconsistencies,
    - Derive insights and make conclusions relevant to marketing and stakeholders.
    - Make recommendations for optimisation.
- Python libraries: pandas, NumPy, Matplotlib Pyplot:
    - Perform exploratory analysis,
    - Calculate performance metrics accurately,
    - Build functions to automate repetitive analyses,
    - Segment customers,
    - Visualise trends over time,
    - Calculate business impact of errors.
- Statistics: Calculate and understand:
    - Indexes,
    - Conversion and retention rates.
    
## Insights

While the first half of the month sticks around 300 users per day, there's a huge spike in the middle of the month. This was due to an email being sent out which reached many users who are not daily visitors of the site. 

By numbers, House Ads gained and retained the most subscribers, while Push gained and retained the least.

By conversiona rate (the ratio of users marketed to by channel to the number of subscribers), Email performed the best. Overall conversion rate for all channels in Jan was 14.09 %. The Email rate is just over twice that, while Push and House Ads is almost half (underperforming). This is a more accurate picture of campaign performance.

Conversion rate drops on the 11th and continues on a downward trend for the much of rest of Jan, with the exception of the email blast in the middle of the month.

Overall retention rate for all channels for Jan was 65.83 %. As you can see, the same as the conversion rates above, Email far outperformed the average retention rate and House Ads has the lowest retention rate.

Retention has a substantial recovery and climb during the middle of the month, coinciding with conversion rate spike for the email blast.

Marketing channels by age: Email is not reaching older age groups, and Facebook is not reaching many people over 55, and Push is not reaching 30-36 or 45-55.

By channel, the most significant findings for trends over days of the week was for Push. Users are about 30% less likely to convert if marketed to via Push on a Fri. Best days are Wednesdays and Thursdays. 

Overall marketing to users over the weekend tends to convert slightly lower intent users, probably best to market most heavily during the week.

Conversion rates were highest throughout the month for age group 19-24 years, they're most responsive to all marketing efforts and a reliable target market.

English speakers make up the majority of your user base, but Arabic and German speakers are 4 to 5 times for likely to convert is marketed to in their preferred language.

Lastly, House Ads could've performed even better, but the channel suffered significant conversion losses from the 11th of Jan due to an implementation error which served ads to all users in English instead of their preferred language. This cost the company 32 subscribers. Measures should be put in place to avoid this in future.
