# YTT Docker Compose Template
This repo has a basic template for generating a docker-compose file for testing purposes. 
Edit variables in `dc.yaml` and the use [ytt](https://github.com/k14s/ytt) to generate 
your `docker-compose.yaml` file by doing the following.

```
ytt -f dc.yaml > docker-compose.yaml
```

then simply pull and run locally using
```
docker-compose pull
docker-compose up
```