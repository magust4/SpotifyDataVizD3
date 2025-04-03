# Song Track Popularity and Streaming Availability Visualizer

This application allows you to search for a song and visualize the popularity of each track within its album. It also displays the countries where the album is available for streaming.

## Features

* **Search Functionality:** Enter a song title to retrieve its album and track data.
* **Track Popularity Visualization:** A visual representation of each track's popularity within the album.
* **Streaming Availability:** Displays a list of countries where the album is available for streaming.

## Prerequisites

* Node.js and npm installed.
* nodemon installed globally (`npm install -g nodemon`).

## Setup

1.  **Clone the repository:**

    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  **Install server dependencies:**

    ```bash
    cd server
    npm install
    ```

3.  **Install client dependencies:**

    ```bash
    cd ../client
    npm install
    ```

## Running the Application

This application requires two terminals: one for the server and one for the client.

**Terminal 1 (Server):**

1.  Navigate to the `server` directory:

    ```bash
    cd <repository_directory>/server
    ```

2.  Start the server using nodemon:

    ```bash
    nodemon server.js
    ```

    This will automatically restart the server whenever you make changes to the server-side code.

**Terminal 2 (Client):**

1.  Navigate to the `client` directory:

    ```bash
    cd <repository_directory>/client
    ```

2.  Start the client:

    ```bash
    npm start
    ```

    This will open the application in your default web browser.

## Usage

1.  Once the application is running in your browser, use the search bar to enter the title of a song.
2.  The application will display the album's tracks and their respective popularity.
3.  You will also see a list of countries where the album is available for streaming.

## Notes

* Ensure that the server is running before starting the client.
* The application relies on an external API (e.g., Spotify API) to fetch song and streaming data. You may need to configure API keys or authentication.
* Nodemon monitors for any changes in your server side code and restarts the server automatically. If you are not using nodemon, you will need to restart the server manually after making changes.
