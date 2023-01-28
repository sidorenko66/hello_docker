# Hello World!

```
docker build . --tag=hello_image
```

```
docker run -d -p 1985:80 --name=hello_cont hello_image
```

```
curl localhost:1985
```