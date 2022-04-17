# portfolio

## はじめだけやること

```
$ docker compose build
$ docker compose run --rm portfolio sh -c "yarn global add create-react-app && create-react-app app --template typescript"
```

## dockerの立ち上げ方
```
$ docker-compose up -d
```
detachで立ち上がる
http://localhost:3001にアクセス


## コンテナの停止
```
$ docker-compose stop
```
