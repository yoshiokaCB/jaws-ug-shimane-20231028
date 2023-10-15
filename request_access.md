# Amazon Bedrock Model access リクエスト手順

1. Amazon Bedrockにアクセスし、「Get Started」をクリックしてください。  
※ この時リージョンが us-east-1（バージニア北部）であることを確認してください。

![Amazon Bedrock](./images/01-amazon-bedrock-top.png)


2. 「manage model access」 をクリックします。

![manage model access](./images/02-model-access.png)


3. claude v2 のパネルにカーソルを合わせ、「model access」をクリックします。

![manage model access](./images/03-base-model.png)

4. 画面右上の「Edit」をクリックします。

![manage model access](./images/04-base-model-edit.png)

5. Antropic の横のEditをクリックすると画像のような入力フォームが表示されますので、必要事項を入力してRequestをクリックしてください。

※ Anthropic の Access Status が Not Requested の場合のみ必要です。

![manage model access](./images/05-request-anthropic.png)

6. Anthropic にチェックを入れて、Save change をクリックします。

![manage model access](./images/06-model-access-check.png)

7. Save 後、Access Status が In Progress になっていることを確認します。

![manage model access](./images/07-result01.png)


8. 数時間時間を空けて、再度アクセスしてください。Access Status が Access Granted になっていることが確認できれば申請完了です。


![manage model access](./images/08-result02.png)


