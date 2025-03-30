# DevOps Project 1

This repository contains the code and configuration files for DevOps Project 1. The primary focus of this project is to demonstrate the use of Docker for containerization and deployment.

https://roadmap.sh/projects/basic-dockerfile

## Table of Contents

- [Project Overview](#project-overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project showcases the use of Docker to containerize applications. It includes Dockerfiles and other configuration files necessary to build, run, and manage Docker containers.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed Docker on your machine. You can download it from [Docker's official website](https://www.docker.com/get-started).

## Installation

To clone and set up this repository locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/subhamgcon/devops-pjt-1.git
    ```

2. Change to the project directory:
    ```sh
    cd devops-pjt-1
    ```

3. Build the Docker image:
    ```sh
    docker build -t devops-pjt-1 .
    ```

## Usage

To run the Docker container, use the following command:
```sh
docker run -d -p 8080:80 devops-pjt-1
