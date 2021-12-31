# Poetry + Docker + JupyterLab

poetryでパッケージの依存関係を自動管理などしてくれる。poetry initをすると、pytestもデフォルトでインストールしてくれる。

dockerでjupyterlabを開いで開発を進める。


## Github Actions
pushをトリガーにpytestを実行する。結果は、slackに通知がいく（ここは各自設定すること）

## Github Pages
https://sakurairihito.github.io/docker_python_temp/

## 参考にしたウェブサイト
poetryとは何か---> https://qiita.com/ksato9700/items/b893cf1db83605898d8a

poetry add jupyterlabをしてから以下の記事に進むこと

docker+poetry ---> https://qiita.com/yolo_kiyoshi/items/332ae902aeb730fbd068
