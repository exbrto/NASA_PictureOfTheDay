NASA Picture of the Day

A simple front-end web app that uses NASA's Astronomy Picture of the Day (APOD) API to display a space image along with its title, date, and explanation.

[!Screenshot](./img/nasaAPI.png)

How It Works
The user picks a date (or loads today's picture).
The app sends a request to NASA's APOD API.
The response is displayed on the page: the image (or video), its title, the date, and NASA's explanation of what you're looking at.
How It's Made

Tech used: HTML, CSS, JavaScript

The page structure is built with HTML and styled with CSS, using normalize.css and reset.css for consistent styling across browsers. JavaScript uses the Fetch API to request data from NASA's APOD endpoint, parses the JSON response, and updates the DOM with the results.


