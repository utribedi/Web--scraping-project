# Web--scraping-project
Web scraping from the movie website "Metacritic"

Goal:
A program that fetches movie information for the top 500 most popular movies from Metacritics. On this website, there is an option to show the top movies. 
On Metacritics, it is called “Movies of All Time”.
The main program asks users for three choices:
1. The 1st option is ‘movie’, when user chooses this one, then your program should ask for the name of a movie (your program should be able to handle all upper and lower cases), your program should find the movie and display the cast information and genre information (Attention: please scrape the full list of cast, not just the short list on the intro page, you will lose 5 points if the full list is not extracted, see example below)
  
2. The 2nd option is ‘people’, when user chooses this one, then your program should ask for the name of an actor/actress, then your program should find the person, and display: (a) all the movies that this person has acted in, (b) a summary of the genres of the these movies

3. The 3rd option is ‘comparison’, when user choose this one, then your program should ask for the names of 2 actors/actresses, then calculate their cosine similarity based on the genre of movies they have acted in
