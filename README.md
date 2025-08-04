# Node.js CI/CD Pipeline with GitHub Actions

This repository demonstrates a complete CI/CD pipeline setup for a Node.js application using GitHub Actions and Docker. The application is a basic Express.js web server that is containerized and pushed to DockerHub through GitHub Actions.

## Tech Stack

- Node.js with Express  
- GitHub Actions  
- Docker  
- DockerHub  

## CI/CD Workflow

The pipeline performs the following steps on every push to the `main` branch:

1. Checkout the repository
2. Set up Node.js
3. Install dependencies
4. Run tests (optional)
5. Build Docker image
6. Push image to DockerHub

The workflow file is located at `.github/workflows/main.yml`.

## DockerHub Image

You can find the Docker image here:  
[https://hub.docker.com/repository/docker/embers10/task1-node](https://hub.docker.com/repository/docker/embers10/task1-node)

## How to Run Locally

### Without Docker

```bash
npm install
npm start
