# Python実行環境


## コンテナ起動

```
docker-compose up -d --build
```

dockerのビルドが不要な場合は`--build`オプションは不要

## コンテナに接続

```
docker-compose exec python3 bash
```

## コンテナを削除する

docker-compose down

## ライブラリを追加する場合

`requirements.txt`にライブラリ名を記載する


