# Simple Docker-Nginx-React-Production

This repository guides you to how to setup React.js application for production build in Nginx and custom domain using docker container

### Domain name

As we have set up custom network and the custom IP address for container in our docker-compose file and we are going to use that container IP to tell our host machine to forward domain to that IP.

### Prerequisite

```
Docker
```

### How to run?

1. Clone the docker-nginx-react repository
2. cd docker-nginx-react
3. docker-compose build && docker-compose up -d
4. `sudo vim /etc/hosts` (you can use any editor) and paste `178.18.1.1 example.com` into it
5. Please enter `example.com` in your browser
