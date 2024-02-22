# mongo-docker
docker-compose file for runnining mongodb in a container connected to a local dataset.

This is a starting point for setting up a mongo db environment using docker where the dataset is stored on the localhost.

For deployment copy the `example.env` file to `.env` and update the variables as indicated.

Run
```
docker-compose up -d 
```
to start the mongo server. Connections can be made at `localhost:27017`
