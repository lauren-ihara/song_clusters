# song_clusters
Perform EDA and cluster analysis to create cohorts of songs.


**Problem Scenario:**

The customer always looks forward to specialized treatment, whether shopping on an e-commerce website or watching Netflix. The customer desires content that aligns with their preferences. To maintain customer engagement, companies must consistently provide the most relevant information.

Starting with Spotify, a Swedish audio streaming and media service provider, boasts over 456 million active monthly users, including more than 195 million paid subscribers as of September 2022. The company aims to create cohorts of different songs to enhance song recommendations. These cohorts will be based on various relevant features, ensuring that each group contains similar types of songs.

**Problem Objective:**

As a data scientist, you should perform exploratory data analysis and cluster analysis to create cohorts of songs. The goal is to understand better the various factors that create a cohort of songs.

**Data Description:**

The dataset comprises information from Spotify's API regarding all albums by the Rolling Stones available on Spotify. It's crucial to highlight that each song possesses a unique ID.


**Steps taken:**
*1.	Initial data inspection and data cleaning:*
- examine the data initially to identify duplicates, missing values, irrelevant entries, or outliers.
- Check for any instances of erroneous entries and rectify them as needed

*2.	Refine the data for further processing based on your findings*

*3.	Perform exploratory data analysis and feature engineering*
- Utilize suitable visualizations to identify the two albums that should be recommended to anyone based on the number of popular songs in each album
- Conduct exploratory data analysis to delve into various features of songs, aiming to identify patterns
- Examine the relationship between a song's popularity and various factors, exploring how this correlation has evolved
- Provide insights on the significance of dimensionality reduction techniques

*4.	Perform cluster analysis*
- Identify the right number of clusters
- Use appropriate clustering algorithms
- Define each cluster based on the features

