# sample-app

A simple Python app (using Flask) which can easily be deployed on [okteto](okteto.com).

To run locally:

```
$ git clone https://github.com/okteto/sample-app.git
$ cd sample-app
$ docker-compose up -d
```

To test the app:

```
curl localhost:5000
Hello World!</br>Hostname: ebf2b5258db0</br>Counter: 1
```
