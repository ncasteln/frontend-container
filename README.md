# frontend-container

This repo is a project initializator, which uses Makefile, Docker and Vite. The container is very useful if you want to create a frontend project without haveing permission to install its related dependencies.

## Try it out!
The project tries to automatize the initialization of a frontend environment, using docker container. Inside `docker-entrypoint.sh` you have the possibility to choose the project you want to initialize (by default here is set to `vanilla-ts`). Check [Vite](https://vitejs.dev/guide/) official documentation.

Once you `make`, a docker image and container are created using the name you give to the project folder. As well you can use the Makefile to stop the container, remove it, remove the image, run bash and check different status.
```bash
$ git clone https://github.com/ncasteln/frontend-container.git <project-name>
$ cd <project-name>;
$ make;
```
