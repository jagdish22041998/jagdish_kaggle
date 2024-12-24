# Disaster_Tweet

**Project Overview**
This project focuses on analyzing and classifying tweets into two categories:

**Disaster-related tweets**: Tweets indicating a natural disaster or emergency.
**Non-disaster-related tweets**: Tweets unrelated to disasters.

** Load Dataset and Import Necessary Libraries **

**Exploratory Data Analysis (EDA):**

Checked the structure, shape, missing values, and duplicate records in the datasets (train_df and test_df).
Visualized the distribution of disaster and non-disaster tweets using a pie chart.

**Word Cloud Generation:**

Concatenated all the tweets for disaster and non-disaster categories separately.
Used the WordCloud library to visualize the most frequent words in disaster and non-disaster tweets.
Created side-by-side visualizations for easy comparison.



**Text Cleaning Script**

We are removing unwanted elements such as URLs, HTML tags, character references, non-printable characters, and numeric values. This preprocessing is essential for ensuring the text data is clean and ready for analysis or modeling.

**Features**

**cleaning steps:**

**Remove URLs**
Using regular expressions, remove all URLs from the text.

**Remove HTML Tags** 
Strips HTML tags from the text.

**Remove Character References**
Removes HTML character references from the text.

**Remove Non-Printable Characters**
Removes characters not in the printable ASCII range.

**Remove Numeric Values**
Removes numeric values and mixtures of alphanumeric content.

**Dataframe Operations:**

The cleaning process is applied to train_df and test_df datasets, creating a new column text_cleaned that stores the cleaned version of the text column.

=========================================================



============================================================


**Text Preprocessing and Visualization****:**


**Lemmatize the Text****:** 

Apply lemmatization to standardize words to their root forms.

**Convert Text to Lowercase****:**

Transform all text to lowercase for uniformity.

**Remove Repeated Characters in Elongated Words****:**

Use a regular expression to reduce exaggerated repeated characters.

**Remove Mentions****:**

Strip user mentions (e.g., @username) using regular expressions.

**Remove Stopwords****:**

Exclude common stopwords to retain only meaningful words.

**Remove Punctuation****:**

Remove punctuation to simplify tokenization and text analysis.

**Generate Word Clouds****:**

Combine text for each category (raw and preprocessed).
Create and display word clouds for both disaster and non-disaster tweets, before and after preprocessing.





