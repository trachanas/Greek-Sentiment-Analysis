# Greek-Sentiment-Analysis

## As a result of my MSc thesis : "Study on Social Media Data" 
<https://dias.library.tuc.gr/view/89031>


## Package rtweet v. 0.7.0

Greek-Sentiment-Analysis Lexicon Based
The following scripts was used to:

- Extract Sentiment of Tweets written to Greek Language
- Perform Network Analysis at words
- Get the most frequent words
 Get the geographic locations of Tweet

 In order to achieve Sentiment Analysis in Greek Language I used the Greek Sentiment Lexicon which you can also find in this repository
 <https://github.com/MKLab-ITI/greek-sentiment-lexicon>
 
 For Network Analysis the code in R was from the below website adjusted to our needs:
<https://juanitorduz.github.io/text-mining-networks-and-visualization-plebiscito-tweets/>
## What you can find in this repository

- _The Scripts_
- _Some Sample files_ :
    1. sentiment analysis data.xlsx (**Data**)
    2. greek_stop_words.csv (**Stop Words**)
    3. emojis.csv (Actually didn't use them yet :smirk:)
- >The graphs
- >Networks

## Using the scripts to

- [x] Establish Connections to Twitter's API
- [x] Data Selection - Data Gathering
- [x] Cleaning - Integration - Storage
- [x] Feature Extraction
- [x] Knowledge extraction
- [x] Visualization
- [x] Bigrams
- [x] Word Network Graphs

## Some Graph to check using Hamming Distance

### Anger

<img src="https://github.com/NKryst/Greek-Sentiment-Analysis/blob/master/Files/Hamming Graphs/Anger.png" width="700" height="500"> |

### Disgust

<img src="https://github.com/NKryst/Greek-Sentiment-Analysis/blob/master/Files/Hamming Graphs/Disgust.png" width="700" height="500">

### Fear

<img src="https://github.com/NKryst/Greek-Sentiment-Analysis/blob/master/Files/Hamming Graphs/Fear.png" width="700" height="500">

### Happiness

<img src="https://github.com/NKryst/Greek-Sentiment-Analysis/blob/master/Files/Hamming Graphs/Happiness.png" width="700" height="500">

### Sadness

<img src="https://github.com/NKryst/Greek-Sentiment-Analysis/blob/master/Files/Hamming Graphs/Sadness.png" width="700" height="500">

### Surprise

<img src="https://github.com/NKryst/Greek-Sentiment-Analysis/blob/master/Files/Hamming Graphs/Surprise.png" width="700" height="500">

### Polarity

<img src="https://github.com/NKryst/Greek-Sentiment-Analysis/blob/master/Files/Hamming Graphs/Polarity.png" width="700" height="500">

### Word Networks 

<img src="https://github.com/NKryst/Greek-Sentiment-Analysis/blob/master/Files/Network Analysis 14-05-2021.png" width="700" height="500">

# What you can find in this repository

- _The Scripts_
- _Some Sample files_ :
    1. sentiment analysis data.xlsx (**Data**)
    2. greek_stop_words.csv (**Stop Words**)
    3. emojis.csv (Actually didn't use them yet :smirk:)
- _The graphs_

# Latest Updates

**February 2021 There were some several additions regarding the following:

- _GreeK Sentiment Lexicon_ : Updating the Polarity Values ( NAs --> 0 , Both --> [average of total values if average = 0 then Both --> 0 , average<0 Both -->-1 ,average>0 Both -->1] new name **Fixed Sentiment Lexicon
- _Emojis Sentiment Lexicon_
- _Sentiment Analysis Revised_ (script) : taking under consideration all the values provided by the annotators of Greek Sentiment Lexicon
- _Addition of Polarity_

**May 2021

- _Addition of Bigram and Network Analysis_
