# arduino_github_actions
version v4.3

# ci

github actionsで実行される

```
.github/
└── workflows/
├── ci.yml # CI オーケストレーター
└── jobs/ # 単一責任ジョブ定義群
├── checkout-setup.yml # リポジトリチェックアウト & ツールチェーン準備
├── format-check.yml # コードフォーマット検証
├── unit-test.yml # ホスト単体テスト (GoogleTest)
├── coverage-report.yml # カバレッジレポート生成 (gcov + lcov)
```