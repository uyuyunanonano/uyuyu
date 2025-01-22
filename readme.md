ASGIで動く  
deployボタンは追加していく予定です  
blog内に静的サイトを入れると認証されていない時にそのサイトが表示されます。  
画像は使えません。  
cookieにyuki=Trueを設定すると認証されます。  
サーバーの起動時に掲示板の公式インスタンスに接続します。定期的にサーバーを再起動してください。  

Renderを使用する場合の手順  
1.githubアカウントを作成する  
2.リポジトリを作る(名前はなんでもいい)(プライベートリポジトリにすることをおすすめします)  
3.import codeを押して https://github.com/mochidukiyukimi/Yuki-Youtube-slim/ と入力  
4.render.yamlを開いて編集(鉛筆のマーク)を押し、nameの横のyuki-youtube-slimをサイトのurlの最初の部分にしたい文字列に変更する。(yuki-yだったらurlはhttps://yuki-y.onrender.comになる)  
5.Deploy to renderボタンを押し、Service Group Nameに適当な文字列を入れてapply(事前にrenderのアカウントを作っておく)
<a href="https://render.com/deploy?repo=https://github.com/taiga905/yuki-youtube-slim-3">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
Azure Web Appのやつだと思います。deployできたら教えて下さい。
<a target="_blank" href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fquickstarts%2Fmicrosoft.web%2Fwebapp-linux-node%2Fazuredeploy.json"><img alt="Deploy to Azure" src="https://binbashbanana.github.io/deploy-buttons/buttons/official/azure.svg"></a>
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy)
