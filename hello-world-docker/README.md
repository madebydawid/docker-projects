# Hello World Docker App

This project demonstrates how to create a simple Nginx web server in a Docker container that serves a basic HTML page. It is an introductory project to Docker and covers the basics of building and running a containerized application.

## Project Structure

- `index.html` - A simple HTML page that says "Hello World, This is Dawid Trying Out Docker!"
- `Dockerfile` - Defines the Docker image, based on the official Nginx image, and copies the HTML file into the container.

## Steps to Run

1. **Build the Docker image:**
   ```bash
   docker build -t hello-world-app .

2. **Run the Docker container:**
   ```bash
   docker run -d -p 8080:80 hello-world-app

3. **Process List of Containers:**
   ```bash
   docker ps -a

4. **Stop Container:**
   ```bash
   docker stop [container-id]

5. **Remove Container:**
   ```bash
   docker rm [container-id]

## Screenshots

- [Screenshot of whole docker process](https://github.com/madebydawid/docker-projects/blob/main/images/full-container-build.jpg?raw=true)

- [Final result in browser window](https://github.com/madebydawid/docker-projects/blob/main/images/hello-world-page.jpg?raw=true)


