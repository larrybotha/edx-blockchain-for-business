# EdX blockchain for business - learning

Learning for https://www.edx.org/course/blockchain-business-introduction-linuxfoundationx-lfs171x

## Getting up and running

Start containers:

```bash
$ docker-compose -f sawtooth-default.yaml up
```

Access client:

```bash
$ docker exec -it sawtooth-client-default bash
```

## Shutting down

After `ctrl-c` to kill docker-compose:

```haskell
$ docker-compose -f sawtooth-default.yaml down
```
