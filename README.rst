===========================
 How to Make PyCon JP 2015
===========================

はじめに
========
このフォルダはCodeZineので連載記事「PyCon JP 2015レポート」の原稿を置く場所です。

Sphinx の環境構築手順
=====================
以下の手順で sphinx をインストールすると、HTMLファイルを作成して参照できます。

::

  $ hg clone ssh://hg@bitbucket.org/pyconjp/codezine-after-reports2015
  $ cd codezine-after-reports2015
  $ virtualenv .venv
  $ . .venv/bin/activate
  (.venv)$ pip install sphinx
  (.venv)$ make html
  (.venv)$ open build/html/index.html
  
