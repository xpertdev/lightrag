# Docker image for LightRAG

Docker image for [LightRAG: Simple and Fast Retrieval-Augmented Generation](https://github.com/HKUDS/LightRAG)

This repository contains the Docker image for the [LightRAG](https://github.com/HKUDS/LightRAG) project. The image is designed to provide a simple and fast environment for running Retrieval-Augmented Generation tasks.

## Build Status

![Build Status](https://github.com/xpertdev/lightrag/actions/workflows/docker-publish.yml/badge.svg)

## Usage

The Docker image is pushed to the GitHub Container Registry and can be pulled using the following command:

```sh
docker pull ghcr.io/xpertdev/lightrag:latest
```

To run the Docker container, use:

```sh
docker run -it -p 9621:9621 -v ./data/rag_storage:/app/data/rag_storage -v ./data/inputs:/app/data/inputs ghcr.io/xpertdev/lightrag:latest
```

## Docker Compose

You can also use Docker Compose to run the container. See the [docker-compose.yml](docker-compose.yml) file for more details.

## LightRAG Repository

For more information about the LightRAG project, visit the [LightRAG GitHub repository](https://github.com/HKUDS/LightRAG).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
