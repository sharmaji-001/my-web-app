# my-web-app
# My Web App

A simple web server built using Node.js and Docker. This project demonstrates how to create a basic web application and deploy it using Docker.

## Features

- Serves a "Hello, World!" message at the root URL (`/`).
- Containerized using Docker for easy deployment and management.

## Technologies Used

- Node.js
- Express
- Docker

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine.
- Basic knowledge of Node.js and JavaScript.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sharmaji-001/my-web-app.git
   cd my-web-app
2. Build the Docker image:docker build -t my-web-app .
3. Run the Docker container:docker run -p 3000:3000 my-web-app
4. Access the web application: Open your browser and go to http://localhost:3000.
