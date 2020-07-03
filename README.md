#### Spring Boot 2
Build the Spring Boot using Java 1.8
```zsh
./gradlew build
```

#### Docker
```zsh
docker login
```

```zsh
$ docker build --tag {yourDockerUsername}/springboot-mongo:0.0.1
```

```zsh
$ docker push {yourDockerUsername}/springboot-mongo:0.0.1
```

#### Kubernetes

```zsh
$ minikube start
```

Kubernetes Dashboard
```zsh
$ minikube dashboard
```

```zsh
$ kubectl apply -f mongo.yml
```

```zsh
$ kubectl apply -f springboot.yml
```

```zsh
$ kubectl apply -f nginx.yml
```


Get the minikube's ip address

```zsh
$ minikube ip
```

```zsh
$ http://{minikubeIP}:32000/api/greeting?name=devlin
```
