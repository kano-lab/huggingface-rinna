# huggingface-rinna
Huggingfaceのrinnaモデルの動作検証用

### やり方(以下、[]の部分は好きな名前をつけてください)

仮想環境を作成する
```
$ mkdir [workdir]
$ cd [workdir]
$ python -m venv [envname]
```

仮想環境をActivateする
```
$ source source [envname]/bin/activate
```

プロジェクトをクローンする
```
$ git clone https://github.com/kano-lab/huggingface-rinna.git
```
必要なパッケージをインストールする
```
$ cd huggingface-rinna
$ pip install -r requirements.txt
```

コードを動かしてみる
```
$ CUDA_VISIBLE_DEVICES=0 python3 chat.py 
```
CUDA_VISIBLE_DEVICESで指定する番号は使うGPUの番号です

空いてるGPUの確認は
ターミナルでnvtopと打つとできます

