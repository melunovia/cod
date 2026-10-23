# まねぶー｜無料マネー診断LP

正式キャラクター画像を含む、スマートフォン向け7問診断LPの動作版です。

## 起動

`python3 -m http.server 8000` をこのディレクトリで実行し、`http://localhost:8000` を開いてください。GitHub Pages等の静的ホスティングで公開できます。

## 公開前の設定

1. `index.html` 内の `https://www.instagram.com/` をまねぶー公式プロフィールURLに変更。
2. 必要ならGTM/GA4を設定。`maneboo_diagnosis_start`, `maneboo_diagnosis_complete`, `maneboo_instagram_click`, `maneboo_share_result` をdataLayerに送信します。
3. スマートフォンで動作・表示を確認。診断結果に表示する投稿はタイトルのみであり、実投稿URLは未設定です。

## 判定ルール

各分野について回答0〜2点（数値が大きいほど見直しの余地がある）を平均し、最大スコアの分野を優先課題として表示。全分野が0.5点以下なら「コツコツ貯金タイプ」。同点は設問定義順で優先。診断は学習のきっかけを提供する簡易チェックであり、正式な金融診断ではありません。

回答内容はサーバーに送信・保存されません。Instagramへのクリックとフォロー完了は別指標です。


## 進捗バーの変更
元のシンプルなLPデザインを維持し、診断画面の進捗バーのみ、ピンクの斜線・白いトラック・ゴール旗に変更しました。
Instagram CTA: https://www.instagram.com/maneboo_official/

## GitHubとURL公開
GitHub Pagesの標準URLに含まれるユーザー名は変更できません。ユーザー名を含めないURLにはCloudflare PagesなどでGitHubリポジトリを接続し、利用可能な *.pages.dev サブドメインを設定してください。GitHubのmainへのpushで自動デプロイできます。


## 進捗バーの変更
元のシンプルなLPデザインを維持し、診断画面の進捗バーのみ、ピンクの斜線・白いトラック・ゴール旗に変更しました。
Instagram CTA: https://www.instagram.com/maneboo_official/

## GitHubとURL公開
GitHub Pagesの標準URLに含まれるユーザー名は変更できません。ユーザー名を含めないURLにはCloudflare PagesなどでGitHubリポジトリを接続し、利用可能な *.pages.dev サブドメインを設定してください。GitHubのmainへのpushで自動デプロイできます。
