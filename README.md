**DOCKER IMAGE**

We'll use https://github.com/jupyter/docker-stacks and the Docker Images are in https://hub.docker.com/u/jupyter

**RUN DOCKER**

docker run -p 8888:8888 jupyter/scipy-notebook:17aba6048f44

Where 17aba6048f44 is the image of the Docker Hub

When you'll run docker you'll see in the terminal the access to Jupyter

**ACCESS TO INSTANCE DOCKER**

docker ps -> View Images Docker running in your computer

docker exec -it _id-image_ bash -> Acces to Instance Docker. Thank to docker ps you'll know the id's Images Docker





