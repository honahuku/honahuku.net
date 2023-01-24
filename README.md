# honahuku.com
ほなふくのポートフォリオ用リポジトリ

## リポジトリのクローン
### 最初のクローン時にsubmoduleを含むクローン
```
git clone --recursive https://github.com/Honahuku/diary-honahuku.git
```
### submoduleだけをクローン
```
git submodule update --init --recursive
```
## よく使うコマンド
### 新規記事作成
```sh
hugo new posts/hoge.md
```

### サーバー立ち上げ
```sh
hugo server -D
```
