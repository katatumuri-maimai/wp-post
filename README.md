# MarkdownからWordpressへ自動投稿
Markdown記法で書いた`.md`ファイルをpushすると、自動でWordPressに投稿できる機能を作っています。  
Markdown形式のファイルをHTMLへ変換して、WordPressに送信します。
今は開発段階です。  

## 現在利用できる機能
- `posts`フォルダに`.md`ファイルを入れてpushすると自動的にワードプレスへ投稿（更新したファイルだけ）
- `code`をGutenbergのcodeブロックへの変換（プラグインcodemirror-blocksのブロックになります）
- 一部のcodemirror-blocksのブロックは言語指定可能

## Futures
- 既存の`.md`ファイルが更新されたとき、自動時にワードプレスの既存記事へ反映  （今は`.md`ファイルが追加されたときのみ、自動投稿できます。）
- 他の人も使えるように整える  （今は自分用です）
- 画像付き記事の投稿
- アイキャッチ画像付で投稿
- Markdownのヘッダーに投稿時の設定を書けるようにする（カスタムURLやカテゴリなど）
- `posts`以下のファイルの検出をpython側で行っているので、Actions側で判断できるようにする
