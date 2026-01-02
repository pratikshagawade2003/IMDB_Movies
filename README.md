## Project Title: Sentiment Analysis on IMDb Movie Reviews

## Project Summary:

In this project, I worked on sentiment analysis using the IMDb movie reviews dataset. The goal of the project was to understand whether a movie review expresses a positive or negative opinion.

First, I focused on cleaning and preparing the text data, because raw text contains a lot of unwanted information. All text was converted to lowercase so that words like “Good” and “good” are treated the same. HTML tags and website URLs were removed since they do not add meaning to the sentiment.

Next, I removed punctuation marks, special characters, and chat words (slang) to make the text cleaner. Emojis were handled by converting them into meaningful words, as emojis often express emotions. Stop words like is, the, and, was were removed because they do not help in understanding sentiment.

After cleaning, the text was tokenized, which means splitting sentences into individual words. To further improve the quality of text, stemming and lemmatization were applied to reduce words to their root or base form. Spelling correction was tested as an optional step, but it was slow and used only when needed.

Finally, the processed data was used to build a sentiment analysis model that classifies movie reviews as positive or negative. This project helped me understand text preprocessing, NLP techniques, and how to work with real-world unstructured data.


## What I Learned from This Project:

How to clean and preprocess text data

Importance of text normalization in NLP

Handling emojis, slang, and noisy text

Basics of sentiment analysis using machine learning
