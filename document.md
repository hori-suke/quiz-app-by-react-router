課題をクリアするためのステップ
 Reactの開発環境を用意
 クイズデータの取得やクイズデータの操作を扱いやすくするモジュール(クラス)を実装する
mochaや jest といったテストツールを使って、動作をテストしながら実装することをオススメする
Reactではjestを使うコードをよく見かけるため、今回は jest を使う
import, exportを使ったテストを行う場合は babel を使う必要がある
Babelを使用する
https://jestjs.io/docs/ja/getting-started#babel-%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%99%E3%82%8B
jestのアサーションメソッド
https://jestjs.io/docs/ja/expect
モジュール実装で利用するライブラリ
QuizFetcher.js
axios
https://github.com/axios/axios
Quiz.js
lodash
https://lodash.com/docs/4.17.15
he
https://github.com/mathiasbynens/he
 トップページ用のコンポーネントと、クイズページ用のコンポーネントを作成して、React Routerを使ってルーティング設定をする
HashRouterを使って実装するようにする
最終的には、実装したクイズアプリをGitHub Pagesを使って公開するため
ポートフォリオの1つにできる
 クイズページ用のコンポーネントで、次の機能を実装する
クイズの読み込み機能
クイズの出題&解答一覧を表示する機能
選択した解答の正解・不正解を判定する機能
クイズ結果を表示する機能
 各ページのスタイル(デザイン)を整える
 必要に応じて、全ページで共通化できるパーツをコンポーネント化する