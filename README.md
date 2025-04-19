# what here

the present repo as part of exercitation for the course DevOps with docker from Helsinki university (God bless those guys!).
exercise 3_1 Your pipeline.

a simple web app will be:
- commited to github
- catched by GitHub Action
- compiled and pushed to docker Hub
- downloaded by watchtower locally to refresh actual container

container not added in docker-compose, pull and run it manually for the first time:
- docker pull username/name_container
- docker run -d -p 8080:8080 username/name_container

## express app

Access with browser http://localhost:8080