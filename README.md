# ocp-service-mesh-foundations

## Build

```shell
$ mvn clean package -Dmaven.test.skip=true -f catalog/java/vertx/pom.xml

$ docker build --rm -t docker.io/jovemfelix/foundation-catalog-service:1.0.0 catalog/java/vertx/

$ docker push jovemfelix/foundation-catalog-service:1.0.0
```



