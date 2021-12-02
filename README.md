# emoji-style

絵文字をスタイルに直接指定することで、地図アイコンとして使えるアイコンサーバー [twemoji-sprites](https://github.com/naogify/twemoji-sprites) の実装デモです。

## ユーザーがカスタマイズする際の手順

* [Use this template](https://github.com/naogify/emoji-style/generate) ボタンでこのリポジトリをコピー。
* `style.yml` を編集。
* しばらくすると `gh-pages` ブランチに `style.json` がコミットされるので、Geolonia Maps で表示する場合は、その URL を以下のように指定してください。

```
<div data-style="https://<あなたのGitHubユーザー名>.github.io/<リポジトリ名>/style.json"></div>
```

例: https://codepen.io/naogify/pen/ZEJOErQ


## 絵文字のカスタマイズ

`layers/poi-<地物名>.yml` というファイルで各地物のアイコンを指定しています。  

例：https://github.com/naogify/emoji-style/blob/main/layers/poi-bus.yml#L25

以下をお好きな絵文字に変更しコミットして下さい。

```
icon-image: 🚌
```

Windows では指定できる絵文字に制限があります。ご了承ください。  

## 参考

twemoji-sprites の詳細については以下の URL をご参考ください。

- https://github.com/naogify/twemoji-sprites
- https://qiita.com/naogify/items/336e4fe19842feb38ea6
