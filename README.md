# 開発環境
## harp.js
静的サイトジェネレータとしてharp.jsを採用。

`/harp.js`以下のファイルをいじり、`harp compile _harp dist`コマンドを打つと、`/dist/`以下に生成されたファイルが格納される。

`gh-pages`ブランチにはdist以下のファイルをデプロイする。

## gh-pages
gh-pagesブランチへデプロイするためにgh-pagesモジュールを採用。

`npm run deploy`コマンドでgh-pagesブランチにデプロイするようになっている。
