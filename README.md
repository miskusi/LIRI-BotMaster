# LIRI Bot
LIRI is a Language Interpretation and Recognition Interface. It will take in commands through the node app and gives you back data.

Commands you can enter:
* `my-tweets`
* `spotify-this-song`
* `movie-this`
* `do-what-it-says`


To Run the LIRI-Bot:
1: node liri.js my-tweets. This will show your last 20 tweets.

2: node liri.js spotify-this-song `<song name here>`
It will show you the following info:
* Artist
* The song's name
* A preview link of the song from spotify
* The album that the song is from

3: node liri.js movie-this `<movie name here>`
* This will output the following information to your terminal/bash window:

    * Title of  movie.
    * Year of the movie.
    * IMDB Rating of the movie.
    * Country where the movie was produced.
    * Language of the movie.
    * Plot of the movie.
    * Actors
    * Rotten Tomatoes Rating.
    * Rotten Tomatoes URL.

   
4: node liri.js do-what-it-says

This will output the command placed in random.txt file
