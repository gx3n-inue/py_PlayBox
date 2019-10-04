# py_PlayBox

MIDI関連のWIN32APIをPythonから呼び出して
楽譜データを演奏します。

qiita.comにて記事を掲載しています。

リンク）  
[python3で演奏する電子オルゴール](https://qiita.com/gx3n-inue/items/d7ae2d4962c41af62fc2)


## サンプルの演奏例

### ・「海の見える街」（楽器：シンセ・多声音色１（new age））
```
python .\py_PlayBox.py .\PB_sample\PB_uminomierumachi.txt 88
```

### ・「崖の上のポニョ」（楽器：明るい生ピアノ）
```
python .\py_PlayBox.py .\PB_sample\PB_ponyo.txt 1
```

第２引数の数値は楽器の指定です。
MIDI音源で定義されている楽器を0～127の値で指定できます。
