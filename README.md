# Travel Buddy Project

This is a simple, single-page web application for planning travel. It is built with HTML, CSS, and JavaScript.

## Features
* Deal Updates
* Pre-Travel Checklist

## How to Run with Docker

1.  **Build the Docker image:**
    `docker build -t travelbuddy-project .`

2.  **Run the container:**
    `docker run -d -p 8080:80 travelbuddy-project`

    *Note: The `-p 8080:80` command maps port 8080 on your computer to port 80 inside the container. You can change the first number to any available port (e.g., `-p 3000:80`).*

3.  **Access the application:**
    Open your browser and go to `http://localhost:8080` (or whichever port you specified, like `http://localhost:3000`).
