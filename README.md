# ReactPractive
## このリポジトリの内容
下記リンクを参考に React + AWS EC2 を利用した Web アプリの開発を学習する
https://medium.com/@rizkiprass/step-by-step-guide-deploying-a-react-app-on-aws-ec2-b2965af05aa4

## ポイント
### React 環境構築
下記のコマンドを実行するとエラーが発生する
```
% npx create-react-app ReactPractice 
```

エラー内容
```
Cannot create a project named "ReactPractive" because of npm naming restrictions:

  * name can no longer contain capital letters

Please choose a different project name.
```

下記のコマンドを実行すること
```
% npx create-react-app reactpractice 
```

### React アプリ実行
下記コマンドを実行
```
% cd reactpractice
% npm start
```
Web ブラウザから下記アドレスにアクセス
```
http://localhost:3000/
```