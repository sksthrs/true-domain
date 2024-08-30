# true-domain

「id:pass@」などが入ったものも含めて、URLからドメイン名を取り出して表示する簡単なスクリプト（を入れたHTMLページ）です。

お試しは以下URLよりどうぞ。
https://sksthrs.github.io/true-domain/

本質的には [URLオブジェクト](https://developer.mozilla.org/ja-JP/docs/Web/API/URL) を作って、`origin`か`hostname`を表示するだけなので、PCでブラウザコンソールを使えば同じことができます。
