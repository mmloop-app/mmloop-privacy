# MmLoop プライバシーポリシーサイト

このディレクトリは、提供中のMmLoopに適用する公式プライバシーポリシーサイトです。アプリのバージョン番号では適用範囲を限定せず、データの取扱いが変わる場合に本文と最終更新日を改定します。
外部JavaScript、外部フォント、Analytics、広告、Cookieを使用しない静的HTML/CSSで構成されています。

## GitHub Pagesで公開する方法

1. 公開用のGitHubリポジトリを作成し、`index.html`と`styles.css`をリポジトリ直下へ配置します。
2. GitHubのリポジトリ画面で、`Settings` → `Pages`を開きます。
3. `Build and deployment`のSourceを`Deploy from a branch`にします。
4. 公開するブランチ（通常は`main`）と`/(root)`を選び、保存します。
5. 表示されたHTTPS URLでページを開き、内容とメールリンクを確認します。

同じリポジトリ内の`docs/`から公開する場合は、このディレクトリの内容を`docs/`へ置き、
GitHub Pagesの公開元として`/docs`を選択してください。

公開URLの例：

```text
https://<GitHubユーザー名>.github.io/<リポジトリ名>/
```

公開後、このURLをApp Store Connectの`Privacy Policy URL`へ設定します。

## 更新時の注意

- ポリシー本文を変更した場合は、`index.html`に記載した「最終更新日」も更新します。
- App Store Connectへ設定する前に、ログインしていないブラウザからHTTPS URLを閲覧できることを確認します。
- MmLoopの実装が変わった場合は、データ保存、OCR、通知、バックアップ、外部通信、広告・Analytics・Trackingの記載を再確認します。
- `styles.css`は相対パスで参照しているため、GitHub Pagesのプロジェクトサイトでも追加設定なしで読み込めます。

