# README-create 
こんにちは  

--- 

## スキル 
html/css  

--- 

## 学習中のスキル 
Javascript  

---

## 装飾変更について  
このプロジェクトでは`Node.js`の**v18**以上が必要です。
`package.json`の`scripts`に`start`コマンドを追加してください。
以前は~yarn~を使っていましたが、現在は`npm`を推奨しています。
`npm run dev`で開発サーバーが起動します。  

---  

## リンクと画像挿入  
[Github公式サイト](http://github.com)  
<img width="2560" height="1600" alt="スクリーンショット (88)" src="https://github.com/user-attachments/assets/5cc21498-2595-4916-bad3-17751aaa7f11" />  

---  

```javascript
const message = "Hello World";
console.log(message);
```
---
## 変更内容
```diff
-const port = 3000;
+const port = process.env.PORT || 3000;
```
```bash
# リポジトリをクローン
git clone https://github.com/user/repo.git
# ディレクトリに移動
cd repo
# 依存パッケージをインストール
npm install
# 開発サーバーを起動
npm run dev
```
```json
{
	"name": "my-app",
	"version": "1.0.0",
	"scripts": {
		"dev": "next dev",
		"build": "next build",
		"start": "next start"
	}
}
```


---

| カテゴリ | 技術 | バージョン |
| :--- | :--- | ---: |
| フレームワーク | Node.js | 1.0 |
| 言語 | Typescript | 1.0 |  

---

