# secure.register.winc.ne.jp 

## 注意事項

### CSSの書き方
基本的にbootstrapを使ってください。bootstrapにはCSSをできるだけ書かなくていい工夫がたくさんあり、font-weightやflexboxなども用意されています。
もし、bootstarpにないCSSが必要な場合は、styleタグの中にCSSを書いてください。

### formatは整えないでください
formatを整える（例えば2スペースのインデントを4スペースに直す）なども、gitの変更に加えられ、conflictした時に差分を確認するのが大変になります。formatを整えたいときは「formatを整える」というissueを出してください。pull reqがはけたらフォーマットを整えます。

### スペースは4つにしてください
HTMLのタグのインデントはスペースキー4つ分にしてください。VS Codeでは、右下の「スペース: 2」から、 「スペースによるインデント」 > 「4」を選択したら変更できます。 

## issueを立ててmergeするまでの流れ
### issueをできるだけ細かく立てる
issueはできるだけ細かくしてください。細かくした分、conflictが起きたときにミスらずにmergeできます。協力お願いします。

例) footerのコピーライトを2019から2022に変更する, 入会申し込みフォームを埋め込む
### branchを切ってください
ブランチを切る前に、必ずdevelopブランチをpullしてください。

#### ブランチの名前と用途
- master 現在の製品バージョン。
- develop 次回リリースの開発用。
#### ブランチの名前の付け方
*は任意の英単語です。
- feature-*  新規機能の開発用。developから分岐し、developへマージする。
- fix-*  developで見つかったバグを修正する。developから分岐し、developへマージする。

例) feature-add-readme, fix-copywrite など


#活動日時
5月からは週1の予定

### branch test
iwaoyuka