# Node.jsを使ったブロックチェーンの実装

# 実行

```
// サーバー立ち上げ
HTTP_PORT=3001 P2P_PORT=6001 npm start
HTTP_PORT=3002 P2P_PORT=6002 PEERS=ws://localhost:6001 npm start

// ブロック作成
curl -H "Content-type:application/json" --data '{"data" : "First block"}' http://localhost:3001/mineBlock
```

# ブロック取得 

```
curl http://localhost:3001/blocks
```

# ブロック作成

```
curl -H "Content-type:application/json" --data '{"data" : "First block"}' http://localhost:3001/mineBlock
```

# Simple blockchain by Node.js 

# RUN 

```
// Run Server
HTTP_PORT=3001 P2P_PORT=6001 npm start
HTTP_PORT=3002 P2P_PORT=6002 PEERS=ws://localhost:6001 npm start

// Create block
curl -H "Content-type:application/json" --data '{"data" : "First block"}' http://localhost:3001/mineBlock
```

# Get Blocks

```
curl http://localhost:3001/blocks
```

# Create Block

```
curl -H "Content-type:application/json" --data '{"data" : "First block"}' http://localhost:3001/mineBlock
```
