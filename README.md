# iu_spotify

## Introduction
I, like many others, have joined the Korean wave in the past few years due to the country's entertainment industry. As I've become a fan of the country and its different celebrities, I've wondered what qualities make up Korean entertainment. Specifically, I am curious about the country's musical attributes, as KPOP has uniquely developed an influence across the world. The Spotify API provides data on a song's popularity and a number of different musical attributes, including energy, danceability, and tempo. Using this data, I will dive into the trends of the singer IU's songs with the assistance of bar charts, scatter plots, and histograms.

For background, IU is a Korean artist who recently won the Artist and Album of the Year honors at Kakao's Melon Music Awards over other popular groups like BTS, NCT Dream, SHINee, and aespa (source). She has a lower global presence compared to BTS, Blackpink, and Girls Generation but is extremely popular within Korea and gives a strong representation of what Korean music is.

The purpose of this exploration of her music is to understand what attributes contribute to IU's most popular songs, how IU's music has changed or stayed the same over time, and how her music compares to popular songs in Korea and around the world. Afterwards, we may have greater insight into the type of music IU will release in upcoming years and how successful those songs will be.

## Spotify API Background
The Spotify API is very developer friendly and was built mainly so that people could integrate Spotify's streaming services into their app or website. Alongside this, Spotify provides an outstanding amount of access to their music database, which allows one to measure different attributes of the songs that they make or love.

This data can be accessed after one registers their account on Spotify's developer portal. Through this registration, you are given a client ID and a secret key, which can be registered through the code shown below.

While you could access the data without any particular package (reference https://stmorse.github.io/journal/spotify-api.html to see how), I am not at that level yet and will be using the already created spotipy package, as it is very well documented.

## Library Considerations
There are many graphing library options that could be used to support this exploration, including matplotlib, seaborn, pyplot, and altair. I have chosen to use plotly, as it automatically provides hover data that one can interact with. This interaction will be useful, as we will be looking at up to 131 datapoints at a time on one graphic.

Plotly supports 40 different graphing options, including the scatter plot, bar chart, and histogram graphics that I will be using in this exploration. It is a free and open-source platform that is available in a number of different programming languages, including Python, R, MATLAB, and Javascript. As stated, it is useful for its interactivity, but it also is widely used because it is easy to operate, has thorough documentation, and creates publication-ready graphics.
