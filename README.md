# Learn Dockerfile with an Angular Project

This repository contains an Angular project that can be easily run using Docker. Follow the steps below to set up and run the project.

## Getting Started

**Note:** Ensure that the `Dockerfile` exists in the `angular-app` directory before proceeding.

### 1. Clone the Repository
```sh
git clone https://github.com/salma1-spec/angualr-app.git
cd angular-app

### 2. Build the Docker Image
```sh
docker build -t angular-app-image .
```

### 3. Run the Docker Container
```sh
docker run -d --name angular-app-container -p 5001:80 angular-app-image
```

## Access the Application
Open your browser and navigate to:
```
http://localhost:5001
```
