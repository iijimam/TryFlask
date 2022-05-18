# Flask+EmbeddedPython

退院時サマリ作成依頼を行う画面イメージが欲しかったのでFlaskとEmbeddedPythonで作ってみました。

参考ページ：https://tech-diary.net/flask-introduction/

## 事前に必要なインストール
- Python

- flaskモジュール
    ```
    pip install flask
    ```
- IRIS（Embedded Python使える新しいバージョンが欲しい）

- Bootstrap

    ここ参照：https://tech-diary.net/flask-introduction/#index_id24

    ダウンロードして展開したら、cssフォルダを　[staticフォルダ](./static)　以下にコピーして終わり
    
## 仮想環境使う場合

ディレクトリを作り（dev01）作ったディレクリに対して以下実行する
```
python -m venv dev01 
```

アクティベートするために以下実行
```
.\dev01\Scripts\activate
```

## アプリの起動
```
python app.py
```
