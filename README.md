# Docker CI/CD Demo

Simple project that builds and pushes a Docker image automatically on every push.

## Local Testing

Build the Docker image:
```bash
docker build -t docker-ci-demo .
```

Run the container:
```bash
docker run -p 8080:80 docker-ci-demo
```

Visit `http://localhost:8080` to see the app.
