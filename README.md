# DOCKER COMPOSE PHPMYADMIN MYSQL

Docker Compose is a tool for defining and running multi-container Docker applications. With Docker Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration. 

Learn more docker compose <a href="https://docs.docker.com/compose/overview/" target="_blank">here</a>

## Playground

1. Clone this repository
```
    git@github.com:simonbustamante/mysql-phpmyadmin-docker-compose.git
```

2. Change to directory
```shell
    cd mysql-phpmyadmin-docker-compose
```
3. Up the compose
```
    docker-compose up -d
```
4. Access phpmyadmin
```
    your_ip:8181
    Server: mysql
    Username: root/user
    Password: root/user
```
5. Access mysql on terminal
```
    docker exec -it dev_db mysql -u root -p
```
