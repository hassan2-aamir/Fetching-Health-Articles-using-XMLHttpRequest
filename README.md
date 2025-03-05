# Fetching Health Articles using XMLHttpRequest

A simple web application that demonstrates how to fetch and display health articles using the XMLHttpRequest API to load data from a local JSON file.

## Project Overview

This project showcases:
- Loading JSON data with XMLHttpRequest
- Dynamically creating HTML elements with JavaScript
- Displaying structured health article information

## Features

- Loads health articles from a local JSON file
- Displays article titles, descriptions, achievement methods, and benefits
- Renders content dynamically without page reload

## Project Structure

- `health_article.html` - Main HTML file
- `health_article.js` - JavaScript logic for fetching and rendering articles
- `health_article.json` - Data source containing health articles

## Getting Started

### Prerequisites

- A local web server (to avoid CORS errors)

### Installation

1. Clone this repository:
    ```
    git clone https://github.com/hassan2-aamir/Fetching-Health-Articles-using-XMLHttpRequest.git
    ```
2. Navigate to the project directory:
    ```
    cd Fetching-Health-Articles-using-XMLHttpRequest
    ```

### Running the Application

**Important:** This project must be served through a local web server to avoid CORS errors. Opening the HTML file directly in a browser will not work properly.

#### Option 1: Using Python's built-in server

```
# For Python 3
python -m http.server

# For Python 2
python -m SimpleHTTPServer
```

Then access the application at `http://localhost:8000/health%20article/health_article.html`

#### Option 2: Using Node.js with http-server

```
# Install http-server globally if you haven't already
npm install -g http-server

# Run the server
http-server
```

Then access the application at `http://localhost:8080/health%20article/health_article.html`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.