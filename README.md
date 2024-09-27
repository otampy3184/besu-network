## 概要

3つのノードで構成されるHyperledger Besuのネットワークを起動する

## 起動方法

```bash
docker compose up -d
```

## 停止方法

```bash
docker compose down
```


## 接続情報

Hardhat等から接続する場合は下記接続情報を設定すること

- HTTP接続：https://localhost:18451
- WebSocket接続: ws://localhost:18541
- chainId: 5151