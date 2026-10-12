しゃくれライオン：ステージ分割版

GitHub Pagesへのアップロード方法
1. このZIPを解凍する。
2. 中身（index.html、stage1.html、stage2.html、boss.html、game.js、game.css、assetsフォルダ）を同じGitHubリポジトリのルートにアップロードする。
3. GitHubの Settings > Pages で main ブランチ / root を公開先に設定する。
4. 公開URLの index.html を開く。

進行条件（仮設定）
・STAGE 1：350点以上でSTAGE 2へ。
・STAGE 2：引継ぎ込み累計750点以上でボス戦へ。
・ボス撃破後、ゴールに到達するとクリア。

容量削減：主人公シートとボス画像をHTML/JS内のBase64埋め込みからassetsフォルダへ分離。3つのステージで共通のgame.jsとgame.cssを使い回す。
