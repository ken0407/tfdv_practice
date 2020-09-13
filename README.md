# tfdv_practice
titanicデータセットを使用してtensorflow-data-validationを動かしてみよう！

実行したpythonのversion: 3.7.4(2020.9現在、tfdvは3.8以上では動きません)

## 使用方法
1. setup.shを実行することでデータの準備を行います。
1. 仮想環境を用意し、パッケージをインストールします。
```
$ python -m venv venv
$ . venv/bin/activate
(venv)$ pip install -r requirements.txt
```

3. tensorflow-data-validation.ipynbを先頭から実行して、データに異常があった場合のTFDVの動作を確認します。
