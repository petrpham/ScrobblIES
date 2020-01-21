# ScrobblIES
This project aims to provide analysis, insights and interesting facts about the data from worldwide-used platform Last.fm. Data used in the project were downloaded using Last.fm API, processed and visualized in Jupyter Notebook with Python kernel.

## What is Last.fm
Last.fm is a site designed for storing user's music library. Users share and track the songs they play on their devices - one such share of a song played is called _scrobble_.

## Last.fm API
Last.fm has its API through which some of the data gathered by the platform can be downloaded and processed. We mainly focused on __data with geographic information__ - most played artists and tracks in given countries. 

## Before use
To access the LastFM public API, one needs an API key, which can granted upon registration @https://www.last.fm/api/account/create. Please insert the key into the configuration file in order to start scraping. To save your time an archived cache file can also be found in this repository containing 100 most popular artists and tracks by country and additional information about them.
