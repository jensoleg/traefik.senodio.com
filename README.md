Traefik setup with Let's Encrypt
================================

[Træfɪk](https://docs.traefik.io/) is a modern HTTP reverse proxy and load balancer made to deploy microservices with ease.

Purpose:
--------
Main purpose for this project is to prebuild a Træfɪk ([Docker](https://www.docker.com/) setup with Let's encrypt integration. 

Installation
------------
Fork this repository and create a sub directory "acme' with an empty acme.json file.
Change the "traefik.toml" file to correspond with your hostname and ports. Also align the port settings in the "docker-compose.yml" file if needed.

Run "docker-compose up -d" to start the docker containers.

Check the status of the traefik container with "docker-compose logs traefik".

Go to the Traefik dashboard by navigating to your site in a browser. 