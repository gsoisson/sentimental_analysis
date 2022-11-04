# sentimental_analysis

The goal of this notebook is to visualize the sentiment of a target user's tweets.

To do so, we perform sentimental analysis of its tweets with CamemBERT, "a state-of-the-art language model for French based on the RoBERTa architecture pretrained on the French subcorpus of the newly available multilingual corpus OSCAR".

We first train the CamemBERT model on a dataset comprised of 5 000 labeled English tweets that have been translated to French via Google Translate. We then apply our model to the 100 latest tweets of a desired user, here @lemondefr.

This gives us a graph of @lemondefr'sentiment over his 100 latest tweets. Finally, by doing a frequency word count, we are able to fetch @lemondefr's top 20 words, and visualize its most positive and negative tweets.
