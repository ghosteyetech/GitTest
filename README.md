# GitTest

> Build docker image
```
  $ docker build --no-cache --tag=sameerat8/cloud-portal-services:1.0 .
```

>Start Docker with a name for in case of need to log into docker
```
  $ docker run --name cloud-portal-service -it sameerat8/cloud-portal-services:1.0
```

> log in to docker using above name (First run docker using above CMD)
```
  $ docker exec -it cloud-portal-service /bin/bash
```
