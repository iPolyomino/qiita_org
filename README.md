

# QiitaOrg

\![Mac OS X-10.13.3](<https://img.shields.io/badge/MacOSX-10.13.3-brightgreen>) \![ruby-2.7.0p0](<https://img.shields.io/badge/ruby-2.7.0p0-brightgreen>) \![qiita\_org version](<https://img.shields.io/badge/qiitaorg-0.1.8-brightgreen>)


## 概要

qiita\_orgはqiitaへの投稿にあたって，テキストの作成から投稿までをterminal上で一括で行いたいというコンセプトでできたgemです．

emacs org-modeで作成したテキストをCUIでqiitaに投稿します．

注意点:command\_lineを使用しているのでrubyのバージョンは2.4.0以上にしてください．また，emacsのバージョンは26.3以上をお勧めします．


## 使用例

まず，org-modeの投稿用テンプレートを取得します．'qiita template'とコマンドを打ち，環境を書き込むかを決めtemplate.orgを作成します．![img](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/612049/76dc9d92-3a77-5523-7a21-571f691402bb.png)

すると，このようなorgが作成されます．![img](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/612049/4a38e62f-9cae-1bf1-ee51-080706c64f6f.png)

ここのtitle,tagをqiitaに載せる用のものに変更してあとは従来通り本文を書くだけ．

本文が作成できたら，あとは投稿用のコマンドを実行するだけ．試しに限定共有投稿へ投稿してみるとこんな感じ．![img](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/612049/3f7179f4-e150-7a63-b8ba-e936b925d7be.png)

ズラズラーっと出ますが，設定がちゃんとできていれば投稿が完了し，Safariで投稿したページが開きます．

投稿した記事にはSouceとしてどこのディレクトリに元のorgテキストがあるか表示されるので，少し前の記事を編集したい時でも便利なはず．．．


## License

The gem is available as open source under the terms of the [MIT License](<https://opensource.org/licenses/MIT>).


# future features

-   qiita post => refactoring

-   configに登録する、git edit global. editor, mail, users&#x2026;
-   qiita config access\_token hogehoge
-   qiita config teams hogehoge
-   giita config =>  configを表示

-   cui, 変数名を適切に選ぶ，teams\_path -> teams\_url
-   qiita getの実装，

