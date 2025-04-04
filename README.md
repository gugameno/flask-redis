## Compose sample application
### Python/Flask application using a Redis database

Project structure:

```
.
├── Dockerfile
├── README.md
├── app.py
├── compose.yaml
└── requirements.txt


```
## Deploy with docker compose
```
$ docker compose up -d

```
## გადადი localhost:8000 in your web browser or run:
```
$ curl localhost:8000
This webpage has been viewed 2 time(s)

```
Stop and remove the containers
```
$ docker compose down

