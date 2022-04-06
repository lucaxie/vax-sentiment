# vax-sentiment
Are vaccination and pandemic trends in Italy related to the sentiment  of the population towards vaccines and the ongoing campaign?

This project, written in Python, is the result of the work of four people that wanted to inquire about the importance of people's general sentiment and emotions on the ongoing campaign to vaccinate the Italian population against COVID-19.

This repository contains 3 files to open with Jupyter Notebook, a folder containing some .py files that modify the behavior of a library used in this project, and many dataset in .csv format, most used to load the data and some that have been created as a way to export the datasets that we refined, for faster data loading.

In particular:
- Jupyter Notebook files, in order:
    • Vaccines Data Analysis - Data cleaning and exploratory data analysis on consolidated data about vaccines, vaccinations and Italy national situation;
    • Data Scraping + Sentiment Analysis - The process of tweet collection and their cleaning to apply sentiment analysis on the text;
    • Conclusions - Merge of the datasets used in the previous parts and exposition of interesting findings and the answer to our R.Q.

- 'Problem Fixing Files (for part 2)' folder: contains 'token.py' and 'url.py', aptly modified for our use. These files substitute regular ones in the twint library.
  N.B.: before running the notebooks, check if these files are in a folder of their own: leaving them in the same folder as 
  the notebooks results in a failed connection with the Python kernel when opening.

- Other files:
    • twitter_scraping 03, twitter_scraping 04-05, twitter_scraping 06-07, twitter_scraping 08-09 and twitter_scraping 10-12: .csv files that contain all tweets written in the specified months that contain some keywords that we chose;
    • data_agg, dataset1 : .csv files that aggregate data on vaccinations, used in the first notebook;
    • final scaled df, final df, Sentiment + Vax, tweets full df, tweets_cleaned, tweets_cleaned_daily, tweets_sent+emo: .csv files that we export while running the notebooks, necessary for compatibility between them;
    • README.txt, this readme file.

Credits go to Luca Xie, Eric Cappellina, Rebecca Galassi, Stefano Torresan for the construction of this project.


Dependencies

• Pandas library
• NumPy library
• Matplotlib library
• Re library
• Shutil library
• Twint library
• Nest_asyncio
• nltk library
• feel_it library
• Seaborn library
• Wordcloud library
• Warnings library
• Datetime library
• Sklearn library
