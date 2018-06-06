# graphql docker image build && docker-compose run

## How to build

* build website(host)

```bash
yarn  && yarn build
```

* build image

```bash
docker-compose build
```

* run

```bash
docker-compose up -d
```

* use  builded

```bash
docker run -d -p 80:80 dalongrong/mygraphql
```