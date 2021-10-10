# おしゃべりハウス

※まだ企画段階です。
Java練習用に、Servlet&amp;JSPでMicrosoft teamsと発言小町と2chを混ぜ合わせたような掲示板サイトを作りたい。

## 条件

### 機能
- ログイン機能
- リアクション（いいね、ハート、怒っている、ぴえん）
- スレ主のコメントが一番上にきて、下に他ユーザー＋スレ主のコメントが続く。スレ主のコメントは枠の色を変えるなどして区別する。
- 投稿したスレッドはスレ主（または管理者）によって終わらせることができる。もしくは1,000コメント行ったら自動でクローズ。
- 「コメント募集中のスレッド」「コメント締め切りのスレッド」がトップページ上に表示されるようにする。デフォは新らしい順で。
- トップページには「新しいスレッドを作成する」ボタンがある。
- ユーザーは自分の投稿であれば削除ができる。

#### 最低限必要な画面
- ログイン画面
- ユーザー登録画面
- ログイン後TOP画面
- 投稿画面

#### エンティティ
ユーザー
アクション種類
スレッド
ユーザーが取ったアクション履歴

### あるとより良い機能
- 「コメント募集中のスレッド」ならば盛り上がっているスレッド（直近のレスとリアクションが多いスレッド）がトップにくるようにする。閲覧数も取れると良い？
- 画像投稿機能。
- ユーザーの通報機能。
- 管理者用の管理画面（他ユーザーの削除、通報履歴の確認 などができる）。
- スレ主は投稿または編集の際に、表題スレにハッシュタグを指定できる。

#### 必要な画面
- 管理画面
    - ユーザー管理画面
    - 通報履歴確認画面

#### エンティティ
ハッシュタグ

