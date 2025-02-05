# Docker Theory Overview

## What is Docker?
Docker is a **platform** used to **develop**, **ship**, and **run** applications inside containers. Containers are lightweight, portable, and self-sufficient environments that encapsulate all dependencies needed to run an application.

## Docker Architecture
Docker follows a **client-server architecture**, consisting of:
- **Docker Client**: Sends commands to Docker Daemon (engine).
- **Docker Daemon (Docker Engine)**: Builds, runs, and manages containers.
- **Docker Images**: Blueprints for creating containers.
- **Docker Containers**: Running instances of Docker images.

## Docker Commands

### Basic Commands:
- `docker run <image>` - Run a container from an image.
- `docker ps` - List running containers.
- `docker stop <container_id>` - Stop a container.
- `docker build -t <name> .` - Build an image from a Dockerfile.

### Docker Image & Container:
- **Image**: A snapshot of the environment needed for your application.
- **Container**: A running instance of an image, isolated and self-sufficient.

## Benefits of Docker
1. **Portability**: Docker containers can run on any system with Docker installed, making it easy to transfer apps across environments.
2. **Consistency**: Developers can ensure the app runs the same way in development, staging, and production environments.
3. **Scalability**: Docker makes it easier to scale applications and manage microservices.

## Docker Use Cases
- **Microservices**: Docker is ideal for breaking applications into small, loosely coupled services.
- **DevOps & CI/CD**: Automate the deployment pipeline using Docker containers.
- **Testing & Development**: Quickly create isolated environments for testing.
