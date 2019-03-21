# nginx-cookbook-docker
This repository contains the source for the NGINX Cookbook using docker. 

## Requirements 
You should have `docker` installed on your machine to run these examples.  


## Run NGINX
```sh
docker run --name nginx -p 9999:80 -d nginx
```

## Test the default site
Open http://localhost:9999/ or use `curl` to test. 
