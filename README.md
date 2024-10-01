[RACS'24] A Hierarchical Topic Modeling Analysis of Twitter Data on COVID-19 Vaccines
Our analysis is performed in the following steps:

1. Dataset Collection:
Our own dataset: Korean twitter mentioning covid-19 vaccine(AstraZeneca, Janssen, Novavax, Moderna, Pfizer) for 4 periods
First period : Feburary 2021 ~ July 2021
Second period : August 2021 ~ November 2021
Third period : December 2021 ~ February 2022
Fourth period : March 2022 ~ January 2023

2. Preprocessing collected data
- removed retweets(official accounts, news, advertisements, unrelated-tweets)
- Pusan National University's spelling/grammar checker to correct sentences
- replaced synonyms

Models : BERTopic, CluHTM, hLDA
Used packages : Python(3.6.9), Okt, Konlpy(0.6.0), Tomotopy(0.12), Gemsim(4.1.2), BERTopic(0.14.1)
