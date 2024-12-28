## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Upgrade dependencies

### Next.js

- `npm` コマンドで Next.js の最新バージョンにアップグレードし、
- `npx @next/codemod` コマンドで必要なコード変更を自動で反映さセル。

```shell
  # 安定版
  npm install next@latest
  npx @next/codemod upgrade latest

  # Canary版
  npm install next@canary
  npx @next/codemod@canary upgrade latest

  npx next --version
```

manual: `npm install next@latest react@rc react-dom@rc`

### npm クリーンインストール

```shell
rm -rf node_modules package-lock.json
npm cache clean --force
npm install
```
