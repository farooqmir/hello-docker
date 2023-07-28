# hello-docker
Simple hello world docker example

Steps:

1. Create a app.js file with desired code. E.g "consolelog("hello docker")
2. Create a Docker file mention node and working directory - refer to the docker file in the repo
3. Run the below command to list docker images
   ```
    docker image ls
   ```
4. Run the below command to login to docker - give username/password
   ```
     docker login
   ```
5. Run the below command to create a tag - example
   ```
      docker tag hello-docker:latest farooqmir/hello-docker
   ```
6. Run the below command to push the image
   ```
   docker push farooqmir/hello-docker:latest
   ```
7. pull the docker image
   ```
     docker push farooqmir/hello-docker:latest
   ```
8. Run the docker image
   ```
    docker run farooqmir/hello-docker
   ```
