Sphinx
-----------------------------
作業メモ。conf.pyにプロジェクトの設定。

導入
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

普段の操作
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
%USERPROFILE%\mysphinx\Scripts\activate
cd 作業フォルダ

#_buildの中身を一度全部消してhtml出力
make clean
make html

設定
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
faviconはペイントで32×32の24ビットビットマップを作成
conf.pyに以下の記述追加
html_title = '昨日の豆腐 tofulog'
html_favicon = 'img/favicon.ico'

Alabasterの設定

文法
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
