# WunderGraph schema extension example

#### Configuration

Check schema extension configuration [doc](https://docs.wundergraph.com/docs/wundergraph-config-ts-reference/configure-schema-extension).

#### Getting started

```shell
docker-compose up

npm install && npm start
```

#### Get Landpad

```shell
curl -N http://localhost:9991/operations/Space
```

#### Get Users

```shell
curl -N http://localhost:9991/operations/Users
```

#### Create User

```shell
curl -d '{"email":"test@wundergraph.com","name":"Test","payload": {"type":"mobile","phone":"12345"}}' -H "Content-Type: application/json" -X POST http://localhost:9991/operations/User
```

## Learn More

Read the [Docs](https://wundergraph.com/docs).

## Got Questions?

Join us on [Discord](https://wundergraph.com/discord)!