# Gassfish dockerfile
Copied from https://www.jujens.eu/posts/en/2015/May/24/deploy-glassfish-docker/ <br/>
It's just EJB glassfish Web 'Hello World' sample.

```sh
cd path/Dockerfile/glassfish
docker build -t glassfish .
docker run -p 9999:8080 --name=glassfish_test glassfish
```

You can see 'Hello World' in localhost:9999/EJB_1/index.html
