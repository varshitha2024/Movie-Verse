# Movie Verse

**Movie Verse** is a web application that allows users to search and explore popular movies. Using The Movie Database (TMDb) API, it displays movie titles, posters, ratings, and descriptions based on search queries. You can also browse a list of popular movies.

## Features

- Browse a list of popular movies.
- Search for movies by title.
- Display movie information such as title, poster, rating, and overview.
- Responsive and user-friendly interface.

## Technologies Used

- **HTML**: For the basic structure of the page.
- **CSS**: For styling the page and making it responsive.
- **JavaScript**: For handling the movie data and interacting with the API.
- **The Movie Database (TMDb) API**: For fetching movie data.

## Getting Started

To get started with the Movie Verse project locally, follow these steps:

### Prerequisites

Make sure you have a modern web browser installed (e.g., Chrome, Firefox).

### Installation

1. Download or clone the repository:
    ```bash
    git clone https://github.com/varshitha2024/movie-verse.git
    ```

2. Open the `index.html` file in your browser.

### Usage

1. Upon opening the page, you'll see a list of popular movies.
2. You can search for a specific movie using the search bar at the top of the page.
3. The results will display movie titles, ratings, posters, and a brief overview.

## File Structure


## API Details

The project uses the following endpoints from the TMDb API:

- **Popular Movies**:  
  `https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=YOUR_API_KEY&page=1`

- **Search Movies**:  
  `https://api.themoviedb.org/3/search/movie?api_key=YOUR_API_KEY&query=`

> Make sure to replace `YOUR_API_KEY` with your own TMDb API key.

## About Me

**Varshitha Vaddi** is a passionate software developer.
## License

This project is open-source and available under the [MIT License](LICENSE).
