Project Description:

**Analyzing Taylor Swift Lyrics with Python**

In this project, I utilized Python to perform a comprehensive analysis of Taylor Swift's lyrics, unraveling intriguing insights into her lyrical patterns and sentiments over the years. The project involves the following key steps:

**1. Loading and Inspecting the Dataset:**
   - Utilized the pandas library to load the dataset containing Taylor Swift's lyrics.
   - Explored the dataset's structure, checking for missing values and variable types.

**2. Adding Essential Data:**
   - Implemented a function to map album names to their respective release years.
   - Created a new column in the dataset, 'album_year,' to incorporate the release years.

**3. Cleaning the Lyric Text:**
   - Lowercased all text, removed punctuation, and excluded stop words to prepare the data for analysis.
   - Stored the cleaned lyrics in a new column named 'clean_lyric.'

**4. Finding Keyword Mentions:**
   - Identified occurrences of the keyword 'midnight' in Taylor Swift's lyrics.
   - Created a new column, 'midnight,' indicating whether a lyric contains the term.

**5. Expanding the Keyword List:**
   - Compiled lists of night, day, and other time-related words.
   - Created regular expression strings for each list and checked for their presence in the lyrics.
   - Counted the frequency of each word category.

**6. Visualizing Time Mentions Over the Years:**
   - Grouped mentions by year and created a line chart showcasing the evolution of night mentions in Taylor Swift's lyrics.

**7. Identifying Albums with Most Night/Day References:**
   - Reinstated album names for the analysis.
   - Sorted and examined the dataset to determine albums with the highest night and day references.

**8. Comparing Day to Night Mentions:**
   - Plotted a line chart displaying both night and day mentions over the years.
   - Explored patterns in how Taylor Swift references time in her lyrics.

**9. Investigating Position of Day vs. Night Mentions Within Albums:**
   - Created a position variable based on track number and line number.
   - Examined the frequency of day and night references by position in the album.

**10. Tokenizing the Lyrics:**
   - Tokenized the words in the 'clean_lyric' column, generating a list of all words used in the lyrics.
   - Analyzed the most frequently used words in Taylor Swift's lyrics.

**11. Analyzing Lyric Sentiment:**
   - Integrated the NLTK library for sentiment analysis.
   - Calculated sentiment scores for each lyric, indicating the positive, negative, and compound sentiments.

**12. Corpus Sentiment Analysis:**
   - Calculated overall sentiment scores for positive, negative, and compound sentiments across all lyrics.
   - Visualized the average sentiment of Taylor Swift's albums over time.

**13. Day or Night? Positive or Negative:**
   - Filtered the dataset for night and day mentions separately.
   - Examined and compared the sentiment scores for night and day references.

This project provides a detailed exploration of Taylor Swift's lyrics, uncovering trends in her use of language, sentiments, and thematic focus over the years.
