# Project Name: Sentiment Analysis on ESG News Headlines of S&P 500 Companies

## Overview
The objective of this project was to perform sentiment analysis on ESG (Environmental, Social, and Governance) news headlines of S&P 500 companies and create a reputation graph to find a correlation with their financial performance. The project used RoBERTa for sentiment analysis and linear regression to generate the reputation graph.

## Data Description
The dataset used in this project included ESG news headlines of S&P 500 companies. The data was collected from various news sources and included information such as the headline text, the company it was associated with, and the date it was published.

## Tools and Technologies Used
The following tools and technologies were used for this project:
- Python programming language
- Numpy library for numerical computations
- Pandas library for data manipulation
- Seaborn library for data visualization
- Matplotlib library for data visualization
- Transformers library for sentiment analysis
- PyTorch library for deep learning
- Plotly library for interactive visualizations

## Methodology
The project used RoBERTa for sentiment analysis of the news headlines. The sentiment analysis was performed on the headline text, and the results were categorized into negative, neutral, and positive sentiments.

Linear regression was then applied to the negative, neutral, and positive emotions on headlines for each company to generate the reputation graph. The reputation graph was used to identify companies with steep gradients of positive/negative emotions and their correlation to their stock market performance.

Finally, the project used Seaborn to create a reputation graph that allowed users to explore the relationship between the emotions of news headlines and the financial performance of S&P 500 companies.

## Results
The analysis of the ESG news headlines dataset revealed several interesting insights. The reputation graph showed that companies with steep gradients of positive/negative emotions had a positive correlation to their stock market performance. This suggests that the sentiment of news headlines can have a significant impact on the financial performance of companies.

## Conclusion
In conclusion, this project demonstrates the potential of sentiment analysis on news headlines to identify patterns and insights related to the financial performance of companies. The results of this analysis can be used to inform future research on the relationship between news sentiment and stock market performance.

## References
- S&P 500 companies list: https://www.spglobal.com/spdji/en/indices/equity/sp-500/
- RoBERTa documentation: https://huggingface.co/transformers/model_doc/roberta.html
- PyTorch documentation: https://pytorch.org/docs/stable/index.html
- Plotly documentation: https://plotly.com/python/
- Transformers documentation: https://huggingface.co/transformers/index.html
