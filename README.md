# docker-portal

create local directory
```
$ mkdir src logs
$ cd src
$ git clone https://github.com/zapbd/honkaku-portal.git
```

docker 
```
$ docker-compose up -d --build
$ docker-compose exec app ash 
```

in docker container
```
$ composer install
```
