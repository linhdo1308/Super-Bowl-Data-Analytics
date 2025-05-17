# Super Bowl LIX 2025 Commercials Analysis

## 1. Overview
This project analyzes Twitter data from Super Bowl LIX commercials in 2025 to uncover key insights around brand sentiment, celebrity endorsements, financial impact, and audience engagement trends. Using Python and Tableau, we processed over 1M rows of tweets to help brands refine future advertising strategies and maximize ROI.

## 2. Key Metrics:
Below are the 3 most important metrics we use to evaluate the performance of commercials
**- Cost per Engagement**

The effectiveness of advertisements was estimated by correlating brand engagement with estimated ad spending impact.

**- Celebrity Mentioned Score**

The mentioned score is determined based on number of hashtags on tweets. 

**- Stock Price Changes**

Brand mentions were analyzed in correlation with stock price fluctuations to assess the financial impact of advertisements. However, it is important to keep in mind that stock price can also be influenced by other factors.


In addition, we also look at:

**- Top 10 Tweeted brands & Top 10 Tweeted Hashtags**

The frequency of ad mentions and hashtags was calculated using pandas.

**- Brand Sentiment Analysis**

Tweets were categorized into positive, neutral, or negative sentiment using NLTK and TextBlob.

**- Tweet Activity Over Time & Quarter Analysis**

Tweet activity was analyzed across different game quarters using Tableau to identify engagement patterns.

**- States of Tweets**

The geographic distribution of tweets across U.S. states was visualized in Tableau.

## 3. Key Insights and Recommendations:
Based on the analysis, some key insights and recommendations can be made for brands to optimize their marketing strategies.
- Commercials featuring NFL players are most well-received by audience. Brands should consider collaborating with these stars in future campaigns to maximize impact.
- Even though TurboTax is one of the most tweeted brands, it also has greatest cost per engagement. Brands should evaluate the cost-effectiveness of their campaigns and explore ways to enhance engagement while managing costs.
- Since most tweets happened during the 4th quarter (50,723 tweets) and after the game (12,203 tweets), brands should plan their ads and social media posts around these times to maximize engagement.
- As Texas, California and Florida demonstrate strong audience engagement, brands should consider targeting their marketing campaigns to these key demographics.

However, it is important to acknowledge the limitations of our analysis. Tweets only represent a subset of the Super Bowl audience and may not fully capture the opinions of groups such as the elderly, who are less likely to use social media. Moreover, stock price fluctuations may be influenced by various micro and macroeconomic factors that go beyond the scope of this analysis.
