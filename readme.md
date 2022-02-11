## npm init -y

## npm i -D @types/express @types/mongoose @types/node @types/nodemon nodemon ts-node typescript express mongoose

## npm i -D prisma

## npm i @prisma/client

## npx prisma init

- prismadir が作成される
- db の設定やスキーマを作成する

### ここまで初期設定

## npx prisma generate

## npm run dev

ESM 対応のため`"type":"modules"`を記載していたところ、
エラー発生

```
TypeError [ERR_UNKNOWN_FILE_EXTENSION]: Unknown file extension ".ts"
```

そのため、`"type":"modules"`を外したところ、コマンド走り成功
