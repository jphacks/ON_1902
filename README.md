# PannelBreak

[![Product Name](image.png)](https://www.youtube.com/watch?v=7iPxiSXJMhE&app=desktop)

## サービスURL
どちらでもアクセスできます。

https://peraichi.com/landing_pages/view/pannelbreak
( https://pannel-break.herokuapp.com/ )

## 製品概要
### Communication × Quiz × Tech

### 背景（製品開発のきっかけ、課題等）
- 今回のプロダクトの開発に至った背景

昔あったとあるランキング形式のクイズ番組から着想を得ました。
ECサイトが普及したことから、商品のリアルタイムの人気の度合いを取得できると考え、それをクイズに用いることで、より楽しいリアルタイム性のあるクイズアプリができるのではと考えました。

- 着目した顧客・顧客の課題・現状

このアプリはよくあるアイスブレイクの場に使えるのではないかと考えています。アイスブレイクは、その場を仕切るファシリテーターのスキルがなければ、参加者の仲が深まることが難しいと思います。そこでこのアプリを使うと、まだ相手のことを知らない中で、一緒にクイズを考えることで自然と仲が深まるきっかけになると考えています。

### 製品説明（具体的な製品の説明）
テーマに沿ったランキングを予想して９つのパネルを正解で埋めていくゲーム。ランキングはweb上のデータによりリアルタイムで変化している。同じテーマでも昨日と今日ではランキングが変わっていることがあるため繰り返しゲームを楽しめる。複数人で遊ぶと盛り上がるため飲み会やレクリエーション等で利用してみて。
### 特長

#### 1. 飽きない：リアルタイムで変化するランキングクイズの為毎日楽しめます。加えてクイズテーマも豊富にできるので自分の知見も増やせるかもしれません。

#### 2. 楽しい：メディア等でよく見るランキングクイズを再現しているつもりなので楽しくないわけないです。1人より2人、2人より３人の方が盛り上がります。

#### 3. 売れる：今回私たちが制作したプロダクトでは商品の売り上げを基にランキングクイズを作成しています。そのため企業側からすれば売れ筋商品をアピールしていることになるため顧客の購買意欲向上を促進する効果があると思います。

### 解決出来ること
私たちは最終的に初対面の人同士が仲良くなれるようなプロダクト作成を目指しています。私たちのプロダクトで遊ぶことでクイズを通して一体感が生まれたり、ランキングの内容について語り合うことで相手のパーソナリティを垣間見るきっかけになります。

### 今後の展望
- オンライン機能

    → オンラインにすることで離れた人とボイスチャットをしながら盛り上がれる

- チーム対戦機能を実装する
    
    → 対戦形式にすることで、一体感がより得られると考えよりコンセプトに沿ったプロダクトになるのではないかと考えた。

- ヒント機能を用意する

    → 全くランキングが分からない時に、話のきっかけとなるようなヒント機能を用意したい

- マネタイズ面

    → 正解時のリンクに、商品のアフィリエイトリンクを載せることで収益化できると考える。また、ユーザー数が増えると、クイズ作成時におすすめするカテゴリーを、企業の広告手段として販売するような事もできると考える。


## 開発内容・開発技術
Webアプリの開発

### 活用した技術
![技術構成図](./tech_stracture.png)

### 研究内容・事前開発プロダクト（任意）
特になし


### 独自開発技術（Hack Dayで開発したもの）
#### 2日間に開発した独自の機能・技術
* 独自で開発したものの内容をこちらに記載してください

    - 運営おすすめのカテゴリー、もしくはフリーワードで、関連する楽天の商品のリアルタイムのランキングクイズを出題できる機能
    - 楽天APIから取得したデータをもとに、回答の選択肢と、答えの情報を生成する機能
    - ドラッグアンドドロップでそれぞれのランクに対する回答ができる機能
    - 正解時に、その商品の説明と楽天市場の商品へアクセスできる機能

* 特に力を入れた部分をファイルリンク、またはcommit_idを記載してください（任意）

    - ドラッグアンドドロップでランキングについて回答できるようにした (https://github.com/jphacks/ON_1902/commit/ea39ce59280aed8c9646ad0895a2f8c793f0a0a4)
    - 正解/不正解時のポップアップを表示できるようにした(https://github.com/jphacks/ON_1902/commit/248e3740a9f6f6d14d9fa14c701cd8ca69ab9c06)
