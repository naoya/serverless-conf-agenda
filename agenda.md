# Serverless Conf / Serverless Geeks Panel

## Talks by each panelists

- [Serverless with a native application for Newspass](https://speakerdeck.com/ymatsuwitter/serverless-with-a-native-application-for-newspass) - y_matsuwitter
- [Unlimited Frameworks](http://www.slideshare.net/slideshow/embed_code/key/cCealgMvuj1XuK) - Masashi Terui
- [紙面ビューアーを支えるサーバーレスアーキテクチャ](https://speakerdeck.com/ikait/serverless-architecture-supports-nikkeis-paper-viewer) - Taishi Ikai

## About Serverless Architectures

- [Serverless Architectures](http://www.martinfowler.com/articles/serverless.html)
- [サーバーレスアーキテクチャという技術分野についての簡単な調査](http://qiita.com/zerobase/items/3bc0d15980b472af841d)
- [FaaS、PaaS、サーバーレスアーキテクチャのメリット](https://www.infoq.com/jp/news/2016/06/faas-serverless-architecture)
- [“Serverless” is just a name. We could have called it “Jeff”](https://serverless.zone/serverless-is-just-a-name-we-could-have-called-it-jeff-1958dd4c63d7#.mrnb2u4lx)

## Services

- [AWS Lambda](https://aws.amazon.com/jp/lambda/)
	- [AWS Mobile Hub](https://aws.amazon.com/jp/mobile/)
- [Functions - Microsoft Azure](https://azure.microsoft.com/ja-jp/services/functions/)
	- [App Service](https://azure.microsoft.com/ja-jp/services/app-service/mobile/)
- [Cloud Functions](https://cloud.google.com/functions/)
	- [Firebase](https://firebase.google.com/)

## vs PaaS
- [Heroku](https://www.heroku.com/)
- [Google App Engine](https://cloud.google.com/appengine/)

## Case Studies

- [Mobile development with Cognito, SNS and Kinesis](https://speakerdeck.com/ymatsuwitter/mobile-development-with-cognito-sns-and-kinesis)
- [マイクロにしすぎた結果がこれだよ！](http://www.slideshare.net/mosa_siru/ss-64839846)
- [iPhoneアプリのバックエンドとしてServerless Framework使ってみた // Speaker Deck](https://speakerdeck.com/mackato/iphoneapurifalsebatukuendotositeserverless-frameworkshi-tutemita)

## Frameworks
- [Serverless Framework](https://serverless.com/)

### AWS API Gateway + Lambda 
- [Python Serverless Microframework for AWS](https://github.com/awslabs/chalice)
- [fluct](https://github.com/fluct/fluct)

## Tools

### Deploy and Manage
- [Lamvery](https://github.com/marcy-terui/lamvery)
	- [Unlimited Frameworks (ServerlessConfセッション紹介)](http://yoshidashingo.hatenablog.com/entry/2016/09/04/191614)
- [Apex](https://github.com/apex/apex)
- [node-aws-lambda](https://github.com/ThoughtWorksStudios/node-aws-lambda)

### Replicate
- [docker-lambda](https://github.com/lambci/docker-lambda)

## Consideration

- [鈴木雄介/Yusuke SUZUKIさんのツイート: &quot;サーバーレスアーキテクチャにすごく期待している人がいるけど、あんなのでアプリ組めるわけないよね？イベント発火としては素晴らしいけども。ストリーム型のイベント駆動と比較して、別の言い方って無いのかな？&quot;](https://twitter.com/yusuke_arclamp/status/778020039194611712)
- [鈴木雄介/Yusuke SUZUKIさんのツイート: &quot;もちろんサーバーレスはとても大事な仕組みなんだけど、現時点で「サーバーレスだけで業務アプリを組む」みたいなことを考える人はアーキテクチャ分かってないなと思う https://t.co/sPyKWKZ0iA&quot;](https://twitter.com/yusuke_arclamp/status/778237843852234752)

### Actor Reactive

- [Reactive Manifesto](http://www.reactivemanifesto.org/ja)
- [Web API サーバーとしての Elixir の可能性](https://speakerdeck.com/naoya/web-api-sabatositefalse-elixir-falseke-neng-xing) / Erlang の Actor モデルとの比較
- [Naoya Itoさんのツイート: &quot;実行に伴うオーバーヘッドが十分に小さければサーバーがなくても毎回処理を起動して破棄すれば、Immutable で shared nothing になり、リアクティブになる。Erlang の Actor モデルと同じ考え方ですよ #serverlessconf&quot;](https://twitter.com/naoya_ito/status/782081868120240129)

### Misc

- [Masashi Teruiさんのツイート: &quot;全てをイベント駆動と捉えて、API GW + LambdaみたいなのはWebhookとかユーザ側・サービス間イベントを伝える手段として捉えると良いんじゃないかなと思ったりします #serverlessconf https://t.co/nZCoWwDJVy&quot;](https://twitter.com/marcy_terui/status/782088392754405376)
- [松本 勇気さんのツイート: &quot;AWSもすごくいいけど、実行リソースが実行単位で立ち上がる仕組みで1番強いのはGoogleAppEngineのGoだと思う。立ち上がりもスケーリングも柔軟でかつ実行環境に豊富なツールが揃ってる。 #serverlessconf&quot;](https://twitter.com/y_matsuwitter/status/782086254422659072)
- サーバーレスアーキテクチャの未来
	- コンテナを飛び越してサーバーレス?
	- [tannaiさんのツイート: &quot;@y_matsuwitter EC2 -&gt; コンテナ -&gt; Lambdaの流れになってて、実行単位の寿命やスケーリング単位がどんどん小さくなっていくってre:Inventでも言ってましたね #serverlessconf&quot;](https://twitter.com/yuukigoodman/status/782085094601207809)

## Pricing

- [AWS LambdaのPricingを読み解く](http://qiita.com/Keisuke69/items/e3f79b50b6039175401b)
- [nekokakさんのツイート: &quot;serverlessの場合て事前の費用見積もりがむずかしくないです？ #serverlessconf&quot;](https://twitter.com/nekokak/status/782085862607552513)
- [松本 勇気さんのツイート: &quot;大量のデータを競技者にぶつけるベンチマーカーをlambdaで運用したけど二日間ガンガン利用されても260円くらいだった。ほんとlambda安い。 #serverlessconf&quot;](https://twitter.com/y_matsuwitter/status/782128999036092416)
