
<p align="left"> 
  <img alt="Top Langs" height="150px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gaia2013&layout=compact&show_icons=true&theme=onedark" />
  <img alt="github stats" height="150px" src="https://github-readme-stats.vercel.app/api?username=gaia2013&theme=onedark&show_icons=ture" />
</p>

- 👋 Hi, I’m Hitoshi Yamaguchi
- 👀 I’m interested in ... system engineering(Ruby AWS GCP), BJJ, U.S.stock, Splatoon3
- 🌱 I’m currently learning ... React.js Library, Next.js Framework, SWE Domain Knowledge
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ... 
- Resume ... https://docs.google.com/spreadsheets/d/1WfGcuWQSwezLkiv0Gb1-onehJR6NenR2PCcVDS1AUs8/edit#gid=1218823470
- Lapras ... https://lapras.com/public/J7KTMYZ

<!---
gaia2013/gaia2013 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->






# Log
##
![IMG_2537](https://user-images.githubusercontent.com/3797539/228577090-64ec8bc7-4950-4bc9-9502-9055ec853f40.JPG)

##
[mysqlpumpを使ってバックアップを取ってみる](https://gihyo.jp/dev/serial/01/mysql-road-construction-news/0153)
##
[モノリシックRailsアプリケーションをモジュラモノリスへ移行しているnoteの事例](https://kaigionrails.org/2022/talks/shshimamo/)
## 2023/03/21

Inside look at modern web browser (part 1)

https://developer.chrome.com/blog/inside-browser-part1/

## 2023/03/20

20 System design concepts explained with images.

https://twitter.com/neetcode1/status/1637110734038654978?s=46&t=tkn1SpMofvWD0GXS2U2jaQ

## 2023/03/19
Reverse Proxy

![FrZmmFbaMAAQylH](https://user-images.githubusercontent.com/3797539/226154793-cd8516a0-27c8-490a-bf93-e33f05624360.jpeg)


stop the world
- アプリケーションで Full GC(ガベージコレクション)が実行されたときに、すべてのアプリケーションスレッドが停止する事象
- ユーザから見るとアプリケーションが停止しているように見える
- GCの時間が長くなるとアプリケーションの停止は無視できないものとなる
- 人間が利用するアプリケーションの場合は、 `200ミリ秒以下` のStop The Worldであれば、通常は考慮しなくてよい
- 人間は、200ミリ秒程度であれば知覚できない
- 低レイテンシのアプリケーションについては、200ミリ秒の停止であっても許されない場合がある
- トレーディングシステムのようなアプリケーションでは、ガベージコレクタの影響に注意する必要がある


## 2023/03/12
Visual Representation of SQL Joins

http://www.codeproject.com/Articles/33052/Visual-Representation-of-SQL-Joins

![SQL JOINS](https://user-images.githubusercontent.com/3797539/224496103-55d32ce8-ef2e-498a-bbf9-92786085f053.png)

## 2023/03/05
技術質問
BackEnd
- 参照渡しと値渡しの違いは？ (Programming)
- ブラウザ開いてから表示されるまで何が起こってる (Network)
- NoSQLとSQLの一般的な違いは？ (DB)
- プロセスとスレッドの違いは？ (OS)
- VMとコンテナの違いは？ (Virtualization)

FrontEnd

- 参照渡しと値渡しの違いは？ (Programming)
- JavaScriptのconst、var、letの違いは何？(JS)
- ページを高速に表示するために出来る事をいくつか教えて (Browser/HTML/JS/CSS)
- CSSの詳細度（Specificity）の考えでは、ID/CLASS/TYPEセレクタのどの優先度で適用されるか？ (CSS)
- Reactの仮想DOMとは何ですか？ (React)
- useMemoはどのような時に使用しますか？(React)



## 2023/03/01
[AWS Client VPM を使ってみた](https://blog.grasys.io/post/ysato/aws-client-vpn/)

## 2023/02/28
[What are the API architectural styles?](https://twitter.com/alexxubyte/status/1630247687114330120?s=12&t=tkn1SpMofvWD0GXS2U2jaQ)

## 2023/02/24


複数ファイルをzipファイルに圧縮するコマンド例
$ zip -r function.zip lambda_function.rb vendor
すでに同名のzipファイルが存在する場合、更新されないので、一旦削除して、zipコマンドを実行する。

include Aws::Record
セミコロン２つ　と　AWSは頭文字だけ大文字

## 2023/02/23
[load balancer と　API　gateway　の違い](https://twitter.com/alexxubyte/status/1628073067468685313?s=12&t=3Csa7Sbd9fKA22wqJf4bKQ)
![FpgTclzaIAA2GYb](https://user-images.githubusercontent.com/3797539/220834736-bd090658-300c-41f2-82ea-d6d615b6d06c.jpeg)

[JWTハンドブック](https://assets.ctfassets.net/2ntc334xpx65/5HColfm15cUhMmDQnupNzd/30d5913d94e79462043f6d8e3f557351/jwt-handbook-jp.pdf)

## 2023/02/22
ゴルフ場検索サービス
FEコード　を　AWS Amplyfy　へ　デプロイ
GoogleMapAPIの有効化
AWS Lambda での関数作成（初期値）


## 2023/02/21

[useEffect完全ガイド](https://overreacted.io/ja/a-complete-guide-to-useeffect/)

[reactの基本がnode.jsだと聞いたのですがどういうことですか？書き方が同じということですか？まだ全くの初心者なのでやさしく教えていただけると助かります。
](https://qr.ae/prWq9y)

[Event.preventDefault()](https://developer.mozilla.org/ja/docs/Web/API/Event/preventDefault)

APIのモックが作れるライブラリ
[json-server](https://github.com/typicode/json-server)

## ~2023/02/20

[MUI Core](https://mui.com/core/)
[仕事ですぐに使えるTypeScript](https://future-architect.github.io/typescript-guide/)

Udemy Coupon page
https://course-lp.vercel.app/ ~2023/02
http://shincode.info/2021/12/31/udemy-discount-coupon/

[Reactの基本的なところ](https://zenn.dev/miz_dev/articles/4e6baa5b747c5d)
