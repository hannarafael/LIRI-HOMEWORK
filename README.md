# LIRI-HOMEWORK 

liri-node-app
Introduction
LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI is a command line node app that takes in parameters and gives you back data.

Setup
Clone the repository

Run npm install, and the following packages should be installed:

Node-Spotify-API

Axios : This module will be used to get the IMDB and BandsInTown API data

Moment

DotEnv

Create a .env file in the same directory as the rest of the files. In the .env file should be:

'# Spotify API keys'

'SPOTIFY_ID=your-spotify-ID-here'

'SPOTIFY_SECRET=your-spotify-secret-here'

liri Available functions:

![Movie-This](https://user-images.githubusercontent.com/49074642/68412619-8ea3b800-015a-11ea-8c37-a49a4ac78b57.png)

![Spotify-This-Song](https://user-images.githubusercontent.com/49074642/68412632-919ea880-015a-11ea-9a4a-3ec2c1509e58.png)

![Concert-This](https://user-images.githubusercontent.com/49074642/68412634-93686c00-015a-11ea-8c24-a7d7f268d6c3.png)

Running the following commands in your terminal will do the following:
node liri.js concert-this 'concert or band name'
This will show the following information about each event to your terminal/bash window:

Name of the Venue

Location of the Venue

Date of the Event

node liri spotify-this-song 'song name'
This will show the following about the song in your terminal/bash window:

Artist(s)

Song Name

Album of the Song

Song Preview Link

If no song is provided then the song "The Sign" will be searched instead

node liri.js omdb 'movie name'
This will output the following information to your terminal/bash window:

Title of the Movie

Year the Movie was Released

The IMDB Rating

Country the Movie was made in

Language the Movie is in

Plot of the Movie

Actors in the Movie

The Rotten Tomatoes Rating

If no movie is provided then the movie "Mr. Nobody." will be searched instead

node liri.js do-what-it-says
The program will take the text inside of random.txt and use it to call the first command with the second part as it's parameter
