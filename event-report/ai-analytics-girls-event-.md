# [第3回] AI × Analytics × 女子部 に行ってきた

## イベントについて
今回で第３回目となる[AI × Analytics × 女子部](https://aigirls.connpass.com/event/102873/)。
会場はウイングアーク１ｓｔ株式会社で、六本木グランドタワーの３６階にある夜景の綺麗な場所でした。

イベントの趣旨としては、AIや機械学習に関する情報共有の他、統計を使った分析やマーケティングなど、AIに関連した幅広いジャンルの発表を通してコミュニティの活性化を図る、とのこと。


[:contents]

<br /><br />
## オープニング(16:30 - 16:35)
AIビジネス推進コンソーシアム 理事 寺澤 豊氏（AI×Analytics×女子部 顧問）<br /><br />


実は仕事が立て込んでおり、オープニングには間に合いませんでした……💦
こちらではAIやTDAに関して、分かりやすく、かつディープな説明があったようです。

[https://www.slideshare.net/YutakaTerasawa/20181114aianalytics:embed:cite]


<br /><br />
## 機械学習/深層学習AI開発プラットフォーム「ReNom」を活用した事例紹介」 (16:35 - 16:55)
株式会社グリッド AIサービス開発グループ セールス　宮﨑 えり子氏<br /><br />

### Renomとは

#### そもそもRenomって？
 - 深層学習のプラットフォーム。
 - ディープラーニングのFMが基盤になっている。
 - githubで無料で使用可能(https://github.com/ReNom-dev-team/ReNom)
 - Renom.jpでチュートリアルを公開中。<br /><br />

#### 登壇者(本職は営業)が使用した感想
 - エンジニアの力を借りずともモデルの構築を行えている。
 - うまくいけば１日１０個のモデルを作成可能。
 - エンジニアが３ヶ月かけていたモデル構築を、営業３人で１週間で完成させることができた。<br /><br />


#### TDAの応用分野
 - 最近であればマーケティングなどに応用されている。
 - その他、金融(クレジットのデータ)など。<br /><br />

### Renomでデータ分析

#### Renomは直感的に操作しやすい
 - GUIでトポロジーを可視化可能。
 - TDAにかけることで高次元のデータを直感的に認識することができる。<br /><br />

#### Renom IMG
 - 画像認識モデルの作成・評価が可能。
 - GUIとAPIが使用できる、自動配布も楽にできる。
 - 精度が低かった場合、タグを付け直して再学習させることで精度の向上が可能。<br /><br />

#### Renom Tag
 - 教師データの作成が可能。
 - GUIでドラッグ＆ドロップで操作する。<br /><br />


<br /><br />
## 「統計の基礎を楽しく学ぼう -箱ひげ図編-」(16:55 - 17:05)
アサヒビジネスソリューションズ株式会社 イノベーション統括部　データ分析チーム 百足山 実花氏<br /><br />


### 箱ひげ図とは

#### 義務教育にも取り入れられている箱ひげ図
- 箱ひげ図とは、データの特長を捉えるために重要な５つの基本統計量を表現したもの。
- 近年、義務教育の内容にも組み込まれた。<br /><br />


#### SNS分析への応用
- 例えば通常のキーワード出現率のグラだと、見る人によってバイアスがかかってしまう可能性あり。
- 箱ひげ図を用いると異常値の検出が可能になる。

[https://www.slideshare.net/YutakaTerasawa/ss-123065329:embed:cite]


<br /><br />
## 「タイタニック号沈没時の生存者について、TDAで見てみた」(17:05 - 17:20)
伊藤忠テクノソリューションズ株式会社 AIビジネス推進部 後藤 仁奈氏<br /><br />


### TDAとは
#### TDAの定義
 - 位相的幾何学を使った分析法。
 - 幾何学：図形や空間の性質を考えること。
 - 位相的：図形や空間の本質を捉える。<br /><br />


#### 分析フロー
- kaggleの「タイタニック生存者予測」データセットを使用
  - 分析の前にTDAで可視化
  - 単純なデータはTDAでなくとも可視化できる。しかし変数が多い複雑なデータは、TDAを使うことで比較的容易に可視化可能。
  - 男女・チケットの値段などで色付けすることで、分析の前に仮説を立てることができた。<br /><br />
- Deep Learningで分析した結果
   - 女性の方が生存者が多い。
   - 男性の場合、チケットの値段が高いほど生存率が高かった。
   - データ分析の予測ができ、事前に仮説を立てることができる。

[https://www.slideshare.net/YutakaTerasawa/20181114-tda:embed:cite]


<br /><br />
## 「Rを使った統計解析のススメ」(17:20 - 17:35)
アサヒビジネスソリューションズ株式会社 イノベーション統括部　データ分析チーム 宮川 彩氏<br /><br />


### Rのススメ
#### 機械学習のとっかかりに
いきなりディープラーニングは難しい。
 - ニューラルネットワークを高度化したものがDeep Learning
 - いきなりディープラーニングではなく、機械学習から始めようと思った人向けのツールである。
 - RとR Studio(IDE)のインストールを勧める。<br /><br />


#### Rとは
 - OSSの統計解析ソフト。
 - 大規模データの解析に最適。
 - エクセルを扱いやすく、グラフ作成と機械学習が可能。<br /><br />


#### 基本統計量
 - 基本統計量とは、データの基本的な特徴を表す値のことで、代表値と散布度に区分できる。
 - プログラムでグラフを作成 →　Rがおすすめ
 - エクセルだと作成が大変だが、Rだと簡単に作成可能<br /><br />


#### 作業フローの例
 - 教師データ・テストデータの作成　→ モデル作成　→　テストデータでのモデル評価
  - それぞれ作成用の関数が用意されている。

[https://www.slideshare.net/YutakaTerasawa/20181114-r:embed:cite]

<br /><br />
## 「デジタルマーケティングってなんでしょう？？」 (17:35 - 17:50 )
アサヒビール株式会社 デジタルマーケティング部 喜多野 美鈴氏<br /><br />


### デジタルマーケティングへどのようにAIを適用できるか
#### AI × ビジネス
 - メディア色々：Paid Media, Earned Media,Owned Media
 - デジタルマーケティングでできること
  - データの取得が可能
  - One to One対応が可能(パーソナライズ化できる)

## 全体まとめ
全体を通して、AIや機械学習についてはほとんど分からない、という参加者にも興味を持たれやすい話が多かったです。
私自身、業務でPHPやPythonを少し触ることはありますが、AIに関しては完全なる素人😅

そんな私でもRenomやRを使ってデータ分析をしてみたい！という気持ちになったので、本当に参加して良かったなあと感じました。
登壇者並びに運営者の皆さま、貴重な機会をいただきありがとうございました✨
