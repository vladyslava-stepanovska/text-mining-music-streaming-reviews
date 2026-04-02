# Text Mining Analysis of Music Streaming App Reviews

A text mining project in R comparing how users perceive **Spotify** and
**Apple Music** through Google Play Store reviews, combining multiple
text analysis techniques to extract marketing insights.

## 📊 Full Report

[View the full analysis here](https://vladyslava-stepanovska.github.io/text-mining-music-streaming-reviews/analysis.html)

## 📋 Overview

This project applies a text mining pipeline to user reviews of music
streaming apps, with a focus on comparing Spotify and Apple Music. By
combining word frequency analysis, sentiment analysis, topic modeling,
and text embeddings, the project explores the differences in how
users perceive the two platforms and translates these into actionable
marketing insights.

## 📂 Project Structure

```         
├── analysis.Rmd                  # Full analysis and code
├── analysis.html                 # Rendered report
└── README.md
```

## 🧩 Methods

-   **Text Preprocessing** — tokenization, stopword removal, stemming
-   **Word Frequency Analysis** — unigrams, commonality and comparison
    clouds
-   **Word Networks** — bigram and trigram network graphs
-   **Sentiment Analysis** — polarity scoring and sentiment over time
-   **Topic Modeling** — LDA with unigrams and bigrams, comparison with
    text2vec
-   **Text Embeddings** — word2vec, UMAP visualization, semantic vector
    arithmetic, cluster dendrograms

## 📦 R Packages

`tm`, `SnowballC`, `dplyr`, `wordcloud`, `RWeka`, `RColorBrewer`, `tidyr`, 
`igraph`, `ggraph`, `tidytext`, `lubridate`, `ggthemes`, `ggplot2`, `syuzhet`, 
`plotly`, `topicmodels`, `text2vec`, `word2vec`, `proxy`, `umap`, `ggrepel`

## 📁 Dataset

Google Play Store reviews for music streaming apps, sourced from Kaggle:
[Google Play Music App Reviews](https://www.kaggle.com/datasets/cluesec/google-play-music-app-reviews)

## 🔍 Key Findings

-   Spotify reviews emphasize **ads, playlists, and discovery
    features**, with more polarized sentiment
-   Apple Music reviews focus on **iTunes integration, subscription
    costs, and technical issues**, with consistently more negative
    sentiment
-   LDA and embedding analyses uncover distinct user pain points for
    each platform
-   Findings are translated into **marketing strategy recommendations**

## 👤 Author

Vladyslava Stepanovska