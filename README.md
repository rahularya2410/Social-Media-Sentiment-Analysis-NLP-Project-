Social Media Sentiment Analysis using NLP
Project Overview
This project analyzes Reddit posts related to artists to understand public sentiment. Using Natural Language Processing (NLP) techniques and the VADER sentiment analyzer, each post is classified into Positive, Neutral, or Negative sentiment categories. The analysis helps artists, brands, and content creators understand audience engagement, feedback patterns, and public perception.

Dataset
Contains 31,948 Reddit posts by users discussing various artists.

Features include the text of the post and VADER-assigned sentiment.

Tools & Technologies
Technology / Library Purpose Python General-purpose data processing & NLP Pandas Load, clean, and manipulate data Matplotlib / Seaborn Visualize sentiment distribution and post features NLTK Stopwords removal, tokenization, lemmatization VADER Lexicon-based sentiment analysis for social media WordCloud Visualize frequent words per sentiment category Scikit-learn Generate confusion matrix, precision, recall, F1-score CSV Export Save sentiment-classified data for reporting

Workflow
Load Dataset – Import Reddit posts.

Text Preprocessing – Remove stopwords, tokenize, lemmatize.

Sentiment Classification – Apply VADER to classify posts.

Visualization – Analyze sentiment distribution, word clouds, post length differences, and keyword frequency.

Model Evaluation – Generate confusion matrix and classification report (100% accuracy expected for lexicon-based sentiment).

Export Results – Save processed dataset for business insights.

Key Insights
Analysis Insight Sentiment Distribution Majority of posts are Positive; Neutral and Negative are less common Word Clouds Positive posts use appreciative words; Negative posts contain complaint-related terms Top Keywords Identify audience priorities, concerns, and engagement topics Post Length vs Sentiment Positive and negative posts are longer → emotional engagement; Neutral posts are shorter Confusion Matrix Matches VADER predictions exactly (100% accuracy)

Note on Accuracy: VADER is lexicon-based; predicted labels match VADER-assigned sentiment. Therefore, evaluation metrics reflect model consistency, not human-labeled ground truth.

Conclusion
The project successfully identifies emotional patterns in social media posts about artists. Insights can guide content strategy, marketing, and audience engagement by understanding public sentiment toward artistic content.
