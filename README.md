# Omdena_KitweChapter_LocalNewsAggregatorAnalyzer

The [data_preprocessing](https://github.com/nemat-al/Omdena_KitweChapter_LocalNewsAggregatorAnalyzer/blob/main/data_preprocessing.ipynb) includes essential steps to clean and prepare raw data for use in the Local News Aggregator and Analyzer. This involves:
-  Loading and Previewing Data: Imports the dataset and checks for basic issues.
-  Cleaning Data: Handles duplicates, and removes missing values.
-  Text Processing: Prepares text fields by normalizing cases, removing special characters, and tokenizing words. In details: Removes URLs, ellipses, and special characters, then tokenizes the text. Words are converted to lowercase, filtered for punctuation and stop words, and lemmatized. The Description column is processed, creating tokens (processed words) and cleaned_text (basic text without URLs) for better readability.
-  Final Output: Structures data for further natural language processing and model analysis.
