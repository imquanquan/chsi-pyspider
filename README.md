##### chsi-pyspider
a pyspider for chsi

#### install
Install docker on the server first.Them:

```
docker run -p 5000:5000 -v /data:/data -d --name pyspiser binux/pyspider:latest
docker build -t chsi-pyspider/nginx .
docker run -p 80:80 -v /data/:data -d --name nginx chsi-pyspider/nginx
```
