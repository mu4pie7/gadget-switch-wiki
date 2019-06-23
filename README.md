# KORG Gadget for Nintendo Switch Wiki
使い方とかメモとか

https://mu4pie7.github.io/gadget-switch-wiki/

[twitter@4piE_7](https://twitter.com/4piE_7)

## Structure

```
├── README.md // ここ
├── book.json // gitbook設定ファイル
├── docs // ビルドして公開するhtmlとかが入る場所
└── src // 元のMarkDownとかを入れる場所　ここにファイルを足していく
    ├── README.md // Wikiトップページ
    ├── hoge // 下層ページ
    └── SUMMARY.md // 左カラム
```

## Usage
何か抜けてそうだけどググればなんとかなるよ（なった）

### gitbookをインストール

```
npm install gitbook-cli
gitbook -V
```


### `src` 配下にページを追加

### htmlをビルドしてcommit
```
gitbook build src/ docs/
```

### このリポジトリにpush
`master` の `docs/` が GitHub Pages として公開される。