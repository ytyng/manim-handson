# 3Blue1Brown の動画を作ってみる


## 3Blue1Brown とは

最高にわかりやすくて面白い数学系 Youtube チャンネル。

https://www.youtube.com/@3blue1brown

公式サイト

https://www.3blue1brown.com/


最近日本語版が出来た。最高。

https://www.youtube.com/@3Blue1BrownJapan


## 動画はどうやって作っている?

Python のライブラリをオープンソースで公開している

https://github.com/3b1b/manim


```shell
brew install ffmpeg mactex

git clone git@github.com:ytyng/manim-handson.git

cd manim-handson

pipenv install

curl -O https://raw.githubusercontent.com/3b1b/manim/master/example_scenes.py

manimgl example_scenes.py OpeningManimExample
manimgl example_scenes.py TextExample
manimgl example_scenes.py TexTransformExample
manimgl example_scenes.py TexIndexing
manimgl example_scenes.py UpdatersExample
manimgl example_scenes.py CoordinateSystemExample
manimgl example_scenes.py GraphExample
manimgl example_scenes.py TexAndNumbersExample
manimgl example_scenes.py SurfaceExample
manimgl example_scenes.py InteractiveDevelopment
manimgl example_scenes.py ControlsExample
```


