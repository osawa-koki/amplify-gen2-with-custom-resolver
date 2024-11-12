# amplify-gen2-with-custom-resolver

🍵🍵🍵 Amplifyでカスタムリゾルバを使ってみる！  

![成果物](./fruit.gif)  

## ローカルでの実行

DevContainerに入り、以下のコマンドを実行します。  

```bash
npx ampx sandbox
```

`./amplify_outputs.json`にバックエンド情報が記載されるまで待ちます。  
`File written: amplify_outputs.json`というログが出力されたら、バックエンドリソースの作成が完了しています。  
このプロセスはキルせず、そのままにしておきます。  

別のターミナルで以下のコマンドを実行します。  

```bash
npm run dev
```

## 参考文献

- [Add custom queries and mutations](https://docs.amplify.aws/nextjs/build-a-backend/data/custom-business-logic/)
- [Custom data access using Lambda functions](https://docs.amplify.aws/nextjs/build-a-backend/data/customize-authz/custom-data-access-patterns/)
