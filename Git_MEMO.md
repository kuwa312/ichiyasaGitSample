# Git学習メモ
## Gitコマンド

-ローカルリポジトリを作る
    -git init
-ファイルの状態を確認
    -git status
-安全なディレクトリとして登録
    -git config --global --add safe.directory C:/~
-全てのファイルを登録する
    -git add -A
-コミット
    -git commit -m "メッセージ"
-ブランチ名をmasterからmainに変更
    -git branch -m main
-リモートリポジトリの追加（ローカルと紐づけ）
    -git remote add <リモートリポジトリ名> <リモートリモートURL>
    -git remote add origin https://<ユーザ名>:<アクセストークン>@github.com/XX/XX.git
-リモートのブランチにアプロード（上流ブランチを設定）
    -git push -u  <リポジトリ名> <ローカルブランチ名>:<リモートブランチ名>
    -git push -u origin main