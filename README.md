#### MIT xPRO Fullstack Development
## FilmFetch App

## Description 
This is a React app called "FilmFetch" that allows users to search for movies using the OMDb API (Open Movie Database).
The FilmFetch App is a user-friendly platform for discovering and exploring movies.  The app is built using JavaScript with the React library. It also uses CSS for styling.  

Functionality:
 - The app fetches movie data from the OMDb API using the fetch function and displays the results.
 - When the user enters a search term and clicks on the search icon, the app sends a request to the API with the search term and retrieves the matching movies.
 - The retrieved movies are displayed as cards using the MovieCard component.
 - The app initializes with a default search term ("Wonder Woman") and displays movies matching this term.
 - If no movies are found for the search term, it displays a message indicating "No movies found."

<img width="554" alt="film-fetch" src="https://github.com/marialee222/film-fetch/assets/150623001/fbfc83ba-d233-4900-bdab-b91b386cb361">


## How to Run
To run the FilmFetch App on your machine, follow these steps: 

	1. First, clone the FilmFetch repository to your local machine using the following command:
	 - git clone https://github.com/marialee222/film-fetch.git

	2. Open a terminal or command prompt and navigate to the directory where you cloned the FilmFetch repository.
 
	3. Before running the app, install the necessary dependencies by running the following command:
	 - npm install 

	4. Once the dependencies are installed, you can start the development server by running:
	 - npm start

	5. After the development server starts, open your web browser and navigate to:
   	 - http://localhost:3000 to view the FilmFetch app.
	You should see the app running with the default search term ("Wonder Woman").
 
	6. Search for movies!
	
## Roadmap of Future Improvements
Future improvements for the FilmFetch App include:
 - Allow users to filter search results by genre, year, rating, etc., to improve search precision.
 - Implement user authentication to allow users to create accounts and save their favorite movies or create watchlists.
 - Allow users to switch between languages dynamically based on their preferences.
 - Ensure the app is accessible to users with disabilities by following best practices for accessibility 
 - Integrate with additional movie databases or APIs to enrich the app's content and provide more comprehensive movie information.
   
:star: Feel free to contribute ideas or collaborate on these enhancements! :star:

### License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
