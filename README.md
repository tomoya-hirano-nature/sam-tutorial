# sam-tutorial
aws samとQveのチュートリアルです

## ディレクトリ構成
```
├── PKG_BackEnd
│   ├── .github
│   │   ├── actions             #GithubActionのWorkFlow内で利用する共通処理化したファイル
│   │   │   ├── python-unit-test
│   │   │   ├── python-yamory-scan
│   │   │   ├── sam-build
│   │   │   ├── sam-deploy
│   │   │   └── create_deployBucket
│   │   └── workflows                           #GithubActionのWorkFlowが格納されています。
|   |
│   ├── kinesis-to-s3　　　　　　　　　# kinesisからs3へのフローで使用するリソースを格納
│   │   └── template.yml
|   |
|   |
|   ├── samconfig.toml                  # デプロイ時の共通設定を記入
|   ├── swagger.yml     
|   └── template.yml                        # 各フローをまとめる

```
