# About
A simple nodejs (w/ typescript) aws lambda with docker container

# Install
```bash
> npm install
```

# Run
```bash
# run the docker container
> docker-compose up
# call que lambda function
> curl -XPOST "http://localhost:9000/2015-03-31/functions/function/invocations" -d '{}'
```

