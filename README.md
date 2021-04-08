### Command to build and run docker image

```Bash
docker build -t express/kubernetes-app .
docker run -p 3000:3000 -d express/kubernetes-app
```