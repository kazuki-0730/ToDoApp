# ToDoApp

webサイト https://zenn.dev/wkb/books/node-tutorial
を参考に簡単なToDo管理アプリケーションを作成しました。

Node.js + Express + MySQL を用いて、ログイン機能やタスクの登録・編集・削除などが行えるようにしています。

#　概要

日々の作業や課題を管理するためのアプリケーションを作成しました。ユーザー登録・ログイン機能を実装し、ログインユーザーごとにタスクを管理できます。

#　主な機能

- ユーザー登録 / ログイン（パスワードはハッシュ化）
- タスクの追加 / 編集 / 削除
- タスクに期限・ステータスを設定
- ログインユーザーごとのタスク表示
- セッション管理（`express-session` + `passport`）

#　使用技術

- Node.js / Express
- MySQL / Knex.js
- Passport.js（認証）
- bcrypt（パスワードのハッシュ化）
- EJS（テンプレートエンジン）
- HTML / CSS（ビューの作成）
