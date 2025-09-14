# Simple DevOps Project

This is a sample project for a course on DevOps, demonstrating a CI/CD pipeline with Jenkins, Ansible, Docker, and Kubernetes.

## Project Overview

This project is a simple Java web application that provides a user registration form. It's a multi-module Maven project with the following components:

*   `server`: Contains the backend server code.
*   `webapp`: Contains the frontend JSP-based web application.

## Prerequisites

*   Java Development Kit (JDK) 1.6 or higher
*   Apache Maven 3.0.3 or higher
*   Docker (for containerization)
*   Kubernetes (for deployment)

## How to Build

To build the project, run the following command from the root directory:

```bash
mvn clean install
```

This will compile the code, run the tests, and create a `war` file in the `webapp/target` directory.

## Deployment

This project is configured for deployment with Docker and Kubernetes. The `Dockerfile` is used to create a Docker image of the application, and the `regapp-deploy.yml` and `regapp-service.yml` files are used to deploy the application to a Kubernetes cluster.
