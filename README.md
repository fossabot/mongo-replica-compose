# mongo-replica-compose
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fisayme%2Fmongo-replica-compose.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fisayme%2Fmongo-replica-compose?ref=badge_shield)

set up mongodb replica locally with docker compose

## How
### start
> make start

#### connect to the mongodb replica
```
docker run --rm -it --network mongodbreplica_default alpine:latest
ping rs0
```

### stop
> make stop


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fisayme%2Fmongo-replica-compose.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fisayme%2Fmongo-replica-compose?ref=badge_large)