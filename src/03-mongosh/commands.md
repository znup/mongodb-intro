## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh LOCAL_DOCKER_URI;
```

```sh
show dbs
show collections
```

```sh
use("p_store")
db.products.find()
```
