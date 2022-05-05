# Git　GitHub　作成テンプレート
## Gitで新規作成
1. gitHubから新規のリポジトリを作成する。
2. ローカルでGitHubにプッシュしたいフォルダを作成する。
3. ターミナルを開く。(Ctrl＋Shift＋＠)
4. ターミナルでGitの初期化  
```
git init 
```
5. Gitにリモートリポジトリを追加する。
```
git remote add origin https://github.com/ichikokoro/Git-Study.git
```
6. Gitにブランチを作成
```
git branch -M main
```
7. GitHubへPushする
```
git push -u origin main
```

## Gitで更新
1. VSの拡張機能でGitのコミットまで行う。
2. GitHubへPushする。
```
git push -u origin main
```