# 和風ストアサイト（縦書きレイアウト模写）

CodeJump初級編の課題として、和風テイストのストアサイトを再現実装しました。  
縦書きレイアウト（`writing-mode`）や、画像上へのテキスト配置、レスポンシブ対応の理解を目的としています。

---

## 使用技術

- HTML5
- CSS3（Flexbox / Position / writing-mode）
- レスポンシブ対応（@media screen and (max-width: 768px)）

---

## 実装内容

- `writing-mode: vertical-rl` を使った縦書きレイアウトの実装（header / news / footer）
- Flexboxによる横並びレイアウトと`row-reverse`による順序制御
- `position: absolute`を使った画像上へのテキスト重ね表示（productsセクション）
- `rgba`による背景透過表現
- `iframe`によるGoogle Map埋め込み
- レスポンシブ対応でのレイアウト調整（不要要素の非表示・サイズ変更）
- `nth-of-type`を使った表示制御（SP時のnews件数制限）

---

## 学んだこと

- `writing-mode`を使った縦書きUIの実装方法を理解した
- `flex-direction: row-reverse`によるレイアウト制御の使い方を習得した
- `position: absolute`でのテキスト配置と親要素との関係を再確認した
- PC→SPへのレスポンシブ設計で「どこを削るか」の考え方を学んだ
- `nth-of-type`による要素制御の実践的な使い方を理解した

---

## 感想

縦書きレイアウト（`writing-mode`）はこれまで触れたことがなく最初は戸惑ったが、  
実装を通してCSSだけで表現できる幅の広さを実感した。

また、画像の上にテキストを配置する実装や、レスポンシブ時の要素削減など、  
実務に近いUI調整の考え方にも触れることができた。

模写ではあるが、「なぜこのCSSが使われているのか」を意識しながら進めることで、  
少しずつ自分で組み立てる力がついてきていると感じている。

---

## 公開URL

👉 https://satoru-tanaka-1977.github.io/codejump-beginner-05-store3/