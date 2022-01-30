# Music-Recommendation-System

# Objective

• Examine the data, I am working with by performing initial Exploratory Data Analysis (EDA). <br>
• Build a basic content recommender system using the concept of Term Frequency-Inverse Document Frequency (TF-IDF) for pattern matching.  <br>
• Build a couple versions of a basic collaborative recommender system using K Nearest Neighbors and Matrix Factorization algorithm.  <br>

# Recommendation System & their types

A Recommender System, or a Recommendation System is a subclass of information filtering system that seeks to predict the "rating" or "preference" a user would give to an item. They are primarily used in commercial applications.  

• A content-based recommender recommends based on history of similar items purchased or interacted with in the past. One can attempt to recommend music that is perceptually similar to what the user has previously listened to, by measuring the similarity between audio signals.  <br>
• A collaborative recommender recommends based on usage trends of similar users. For instance, if Alice and Bob like movies X, Y and Z, and you like movies X and Y, you may be recommended movie Z.

# Data
For Content based recommendation system-
• I used dataset songdata.csv which contains name, artist, and lyrics for 57650  <br>
songs in English. The data has been acquired from LyricsFreak through scraping.  <br>
 <br>
For Collaborative filter recommendation system
• I am going to use the Million Song Dataset, a freely-available collection of audio features and metadata for a million contemporary popular music tracks. <br>
• There are two files- first one contains user_ID, song_ID and listen_count and other contain song ID, title of that song, release, artist name and year and we merge these two files using song_ID. <br>
• In the Dataset, we have- 2000000 observations , 9567 unique songs , 3375 unique artists , 76353 unique users <br>

# Results

![alt text](https://github.com/yashikesarwani/Music-Recommendation-System/blob/master/ss/R1.png?raw=true)

![alt text](https://github.com/yashikesarwani/Music-Recommendation-System/blob/master/ss/R2.png?raw=true)

![alt text](https://github.com/yashikesarwani/Music-Recommendation-System/blob/master/ss/R3.png?raw=true)
