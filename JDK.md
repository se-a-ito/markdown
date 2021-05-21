# JDKのインストール・環境構築

## 1.Oracleのサイトから自分のOS等にあったJDKをインストールする。
[Oracle公式](https://www.oracle.com/java/technologies/javase-downloads.html)
## 2.環境変数の詳細設定
コントロールパネル→システム→システムの詳細設定からシステム環境変数「Path」の設定を行う。
ダウンロードしたJDKのパスを通してあげる。<br>
※環境変数にJAVAがなければ変数名は多分何でもいいと思うからpathを通してあげる。例:JAVA_HOMEとかとか

## 3.環境変数の設定ができたか確認する。
> javac -version<br>

コマンドラインでjavac のバージョンが表示されれば完了。