# apriori-market-basket-analysis
Market basket analysis on IMDB dataset

This project applies market basket analysis to the IMDB Top 1000 Movies and TV Shows dataset. Movies are treated as transactions and actors as items, with the goal of finding groups of actors who frequently appear together.

The analysis uses a from-scratch implementation of the Apriori algorithm, with a minimum support threshold of 0.5% (at least 5 appearances out of 1000 films). The most frequent pattern found is the Harry Potter core trio (Daniel Radcliffe, Emma Watson, Rupert Grint), which co-appears in 5 films in the dataset.

The repo also includes a small scalability experiment measuring how runtime grows as the dataset size increases.
