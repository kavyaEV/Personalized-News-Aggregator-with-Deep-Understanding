# Personalized-News-Aggregator-with-Deep-Understanding
 an AI that curates personalized news feeds with summaries, sentiment analysis, and contextual explanations. It could highlight key points, provide historical context, and even suggest similar articles. The AI would use natural language processing to understand the user's interests and biases, providing a balanced view.
# Personalized News Aggregator
# Overview
The Personalized News Aggregator is an AI-powered application that fetches, summarizes, and analyzes news articles based on user-defined keywords. The project leverages natural language processing (NLP) techniques to provide a personalized news feed, including sentiment analysis and text summarization.

# Features
 Fetch News: Retrieves news articles from NewsAPI based on user queries.
 Text Summarization: Summarizes the content of articles using a pre-trained transformer model.
 Sentiment Analysis: Analyzes the sentiment of the summarized text to provide a sense of the article's tone.
 Personalization: Allows users to input keywords of interest, customizing the news feed accordingly.
 Methodology
 News API Integration: The project uses NewsAPI to fetch the latest news articles based on the user's keywords. The API key must be obtained from NewsAPI and set in the script.

## Text Summarization: The transformers library's pipeline function is used to summarize the articles. It leverages a pre-trained model capable of distilling the essence of the article into a concise summary.

## Sentiment Analysis: Sentiment analysis is conducted using TextBlob, a Python library that processes textual data and assigns a sentiment polarity score ranging from -1 to 1, indicating negative to positive sentiment.

## Data Storage: The results are stored in a pandas DataFrame and can be exported to a CSV file for further analysis or reporting.
