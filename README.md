# About this Repo

This is clone repo from the official Docker image for [nginx](https://registry.hub.docker.com/_/nginx/).

##建立映像檔，並取名為'kaemiin/nginx:v1'
```
docker build -t="kaemiin/nginx:v1" .
```
##查看映像檔建立情況
```
docker images
```

##改以8080 啟動
```
docker run --name local-nginx -d -p 8080:80 kaemiin/nginx:v1
```
##查看目前IP address
```
docker-machine ip devops
```
##使用瀏覽器檢視
```
http://192.168.99.100:8080
```

