# liri-node-app

<h2><b>Overview</b></h2>

Have you heard of SIRI? Well, meet LIRI. While SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.



<h3><b>Technologies Used:</b></h3>
Javascript
Node
Command Line
Twitter API
Spotify API
OMDB API


<h3><b>Node Packages Used:</b></h3>
dotenv
node-spotify-api
request
spotify
twitter




<b><h3>liri.js can take in one of the following commands:</h3></b>
* `my-tweets`

* `spotify-this-song`

* `movie-this`

* `do-what-it-says`





<b><h3>What Each Command Should Do</h3></b>

1. node liri.js my-tweets
This will show your last 20 tweets and when they were created at in your terminal/bash window.

2. node liri.js spotify-this-song '<song name here>'
This will show the following information about the song in your terminal/bash window

Artist(s)
The song's name
A preview link of the song from Spotify
The album that the song is from


3. node liri.js movie-this '<movie name here>'
This will output the following information to your terminal/bash window:

   * Title of the movie.
   * Year the movie came out.
   * IMDB Rating of the movie.
   * Rotten Tomatoes Rating of the movie.
   * Country where the movie was produced.
   * Language of the movie.
   * Plot of the movie.
   * Actors in the movie.

If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'

If you haven't watched "Mr. Nobody," then you should: http://www.imdb.com/title/tt0485947/
It's on Netflix!


4. node liri.js do-what-it-says
Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.

It should run spotify-this-song for "I Want it That Way," as follows the text in random.txt.
