Docker base with docker-compose, one container for nginx, one container for php7 and one mysql. Is for dev.

for mac user => install [docker-machine](https://docs.docker.com/machine/install-machine/)
and [docker-compose](https://docs.docker.com/compose/install/)

In root dir:
* docker-compose build
* docker-compose up -d
* docker ps

if you have 3 running container, it's good.
## be carreful, datas mysql is in container and not saved. If you delete or rebuild container, you lose the datas   


is for use dev symfony project (conf nginx) or other if you want
install composer and php in your machine for launch cmd in your terminal

### For generate project symfony

* cd code
* composer create-project symfony/framework-standard-edition project
