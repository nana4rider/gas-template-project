# GASテンプレートプロジェクト

## 初期設定
* プロジェクト名を置換  
```sed
s/gas-template-project/[New Project Name]/g
```
* モジュールのインストール
```
npm install
```
* GASプロジェクトの作成
```
npm run create
```
* .clasp.jsonのrootDir書き換え
```json
{"rootDir": "dist"}
```

## プロジェクトのデプロイ
```
npm run deploy
```

## appsscript.jsonのダウンロード
```
npm run pull
```
