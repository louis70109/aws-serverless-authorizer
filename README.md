# AWS-serverless-authorizer

- [Serverless framework](https://serverless.com/)
- Flask - [serverless-wsgi](https://github.com/louis70109/aws-serverless-authorizer/blob/master/serverless.yml#L28)
- API Gateway - [Authorizer](https://github.com/louis70109/aws-serverless-authorizer/blob/master/serverless.yml#L18)


# Quick Start

1. 安裝全域的 `serverless` 指令或是之後你可以使用 `npx` 來避免安裝。

```bash=
npm install -g serverless
```

2. 如果你還沒有用 [aws-cli](https://aws.amazon.com/tw/cli/) 的話你需要設定你的 **AWS** 憑證。

```bash=
export AWS_ACCESS_KEY_ID=<your-key-here>
export AWS_SECRET_ACCESS_KEY=<your-secret-key-here>
```

3. 安裝 serverless 相依套件以及 flask 套件。

```bash=
npm install
pip install -r requirements.txt
```

4. 部署
下面兩個指令選一個用，含有 npx 的部分則是透過 npm 去遠端套件庫**暫時**使用套件的一個指令。
```bash
serverless deploy
# npx serverless deploy
```
# License

[MIT](https://github.com/louis70109/aws-serverless-authorizer/blob/master/MIT-LICENSE)
