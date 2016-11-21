# docker4begginers

The "docker-compose.yml" contain 2 services. It contains 2 services that used two images, the first is "web-ubuntu-php7-apache2" and the second "vinnyfs89 / db-debian-mysql" that are linked by the command "links". Both can be manually downloaded via the link "https://hub.docker.com/r/vinnyfs89".

Execute the command below:
```
  docker-compose up --build -d
```  
To see the running containers execute the command below:
```
  docker ps
```  
If do you want to enter in bash of those containers execute the command below using the container id showed:
```
  docker exec -ti  {container_id} bash
```  
-------

@todo : fill this place with most used commands for Docker Platform
