# Movie Picker

A web application that helps you discover movies based on your preferences.

## Description

Movie Picker is a user-friendly web application that allows you to find movies to watch based on various criteria such as genre, era (decade), language, country, rating, and runtime. It fetches movie data from The Movie Database (TMDB) API and displays the results in an attractive and interactive interface.

## Features

*   **Advanced Search:** Filter movies by genre, era, language, country, minimum IMDb rating, and maximum runtime.
*   **Sort Options:** Sort the results by popularity, rating, or release date.
*   **Random Movie:** Get a random movie suggestion from the current search results.
*   **Movie Details:** View detailed information about each movie, including its overview, rating, and release date.
*   **Watchlist:** Add movies to your personal watchlist, which is saved in your browser's local storage.
*   **Responsive Design:** The application is designed to work on both desktop and mobile devices.

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/movie-picker.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd movie-picker
    ```
3.  **Get your TMDB API Key:**
    *   Go to [https://www.themoviedb.org/signup](https://www.themoviedb.org/signup) and create an account.
    *   Go to your account settings, then to the "API" section and get your API key.
4.  **Add your API Key:**
    *   Open the `index.html` file.
    *   Find the line `const apiKey = 'YOUR_TMDB_API_KEY';`
    *   Replace `'YOUR_TMDB_API_KEY'` with your actual TMDB API key.
5.  **Open `index.html` in your browser:**
    *   You can simply double-click the `index.html` file to open it in your default web browser.

## Deployment on GitHub Pages

You can host this application for free on GitHub Pages.

1.  **Push your code to a GitHub repository.**
2.  **Go to your repository's settings.**
3.  **In the "Pages" section, select the branch you want to deploy from (usually `main` or `master`).**
4.  **Select the root folder and save.**
5.  **Your application will be available at `https://your-username.github.io/your-repository-name/`.**

## Technologies Used

*   HTML
*   CSS
*   JavaScript
*   [The Movie Database (TMDB) API](https://www.themoviedb.org/documentation/api)
