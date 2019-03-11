# LIRIBOT
LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

## LIRI uses the following commands:
```
spotify-this-song
```
```
movie-this
```
```
do-what-it-says
```
## Technologies used:

* Node.js
* Javascript

## npm packages: 
* [Axios](https://www.npmjs.com/package/axios)
* [spotify](https://www.npmjs.com/package/node-spotify-api) - A simple to use API library for the Spotify REST API.
* [request](https://www.npmjs.com/package/request) - Request is designed to be the simplest way possible to make http calls. It supports HTTPS and follows redirects by default.
* [dotenv](https://www.npmjs.com/package/dotenv) - Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env.
* [Moment](https://www.npmjs.com/package/moment)

## How to Run LIRIBOT
1.  `node liri.js spotify-this-song '<song name here>'`

   * This will show the following information about the song in your terminal/bash window

     * Artist(s)

     * The song's name

     * A preview link of the song from Spotify

     * The album that the song is from

   * If no song is provided then your program will default to "The Sign" by Ace of Base.
   
  2. `node liri.js movie-this '<movie name here>'`

   * This will output the following information to your terminal/bash window:

     ```
       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.
     ```

   * If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'

     * If you haven't watched "Mr. Nobody," then you should: <http://www.imdb.com/title/tt0485947/>

     * It's on Netflix!
     
    3.  `node liri.js do-what-it-says`

   * Using the `fs` Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.

     * It should run `spotify-this-song` for "I Want it That Way," as follows the text in `random.txt`.
     
     ## Screenshots
     
   <img width="594" alt="do-what-it-says" src="https://user-images.githubusercontent.com/43947587/54097650-5a2ef080-436e-11e9-998f-a9bc89fe72af.png">
<img width="567" alt="movie-this" src="https://user-images.githubusercontent.com/43947587/54097651-5a2ef080-436e-11e9-8584-df13a49e423d.png">
<img width="570" alt="movie-this-default" src="https://user-images.githubusercontent.com/43947587/54097652-5a2ef080-436e-11e9-824b-126e4caa3fee.png">
<img width="530" alt="spotify-this-song" src="https://user-images.githubusercontent.com/43947587/54097653-5a2ef080-436e-11e9-809e-f9881ed085d6.png">
<img width="572" alt="spotify-this-song-default" src="https://user-images.githubusercontent.com/43947587/54097654-5a2ef080-436e-11e9-86c4-5ac69ba850aa.png">


