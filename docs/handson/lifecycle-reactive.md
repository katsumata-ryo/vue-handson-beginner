# ライフサイクルフックとリアクティブシステム

## この演習で学習する内容
- Vueインスタンスのライフサイクルフック
- リアクティブシステム

## 演習内容
[前の演習](./hello-world.md)で作成した`Hello World!`を表示するアプリケーションを、以下のように変更してみてください。

- Vueインスタンスがマウントされた際に呼び出される`mounted`フックを使って、フック内で、2秒後に画面に表示された`Hello World!`適当なメッセージ(例:`こんにちは、世界！`)に変わるようにデータ`message`を変更する
- 監視プロパティ`watch`でデータ`message`を監視して、内容を`console.log`に出力するようにする

Vue.jsのライフサイクルフックとデータの変更に伴うリアクティブシステムの動作を確認しましょう。

## 参考: 公式ドキュメント
- [Vueインスタンス](https://jp.vuejs.org/v2/guide/instance.html)
- [API - オプション/ライフサイクルフック](https://jp.vuejs.org/v2/api/#%E3%82%AA%E3%83%97%E3%82%B7%E3%83%A7%E3%83%B3-%E3%83%A9%E3%82%A4%E3%83%95%E3%82%B5%E3%82%A4%E3%82%AF%E3%83%AB%E3%83%95%E3%83%83%E3%82%AF)
- [API - watch](https://jp.vuejs.org/v2/api/#watch)

## 解答例
- <answer-link url="/examples/lifecycle-reactive.html">こちらを参照</answer-link>
