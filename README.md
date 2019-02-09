# installing ionic globally

npm install -g ionic

# create the ionic app with angular
ionic start ionic-movie-app blank --type=angular

# dive into the ionic app
cd ionic-movie-app

# create the pages or components
ionic g page pages/movies
ionic g page pages/movieDetails
ionic g service services/movie

# run the ionic app
ionic serve

# install the ionic lab to see the output in ios, android or in windows platform
npm install @ionic/lab

# run the ionic lab and check the output in ios/android/windows platform
ionic lab


# extra information about the api key
apikey: http://www.omdbapi.com/?i=tt3896198&apikey=d3c1c9a0
