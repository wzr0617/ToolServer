# ToolServer

## Shellとは
https://www.runoob.com/linux/linux-shell.html
Shell 是一个用 C 语言编写的程序，它是用户使用 Linux 的桥梁。Shell 既是一种命令语言，又是一种程序设计语言。
Shell 是指一种应用程序，这个应用程序提供了一个界面，用户通过这个界面访问操作系统内核的服务。
Ken Thompson 的 sh 是第一种 Unix Shell，Windows Explorer 是一个典型的图形界面 Shell。

Linux 的 Shell 种类众多，常见的有：
Bourne Shell（/usr/bin/sh或/bin/sh）
Bourne Again Shell（/bin/bash）
C Shell（/usr/bin/csh）
K Shell（/usr/bin/ksh）
Shell for Root（/sbin/sh）
zsh (/bin/zsh)

## zshとは
Shell の一つです 
https://support.apple.com/ja-jp/HT208050


## pythonインストール：
https://prog-8.com/docs/python-env

## pythonのバージョン切り替える際、問題ある場合下記を参照
https://blog.serverworks.co.jp/2021/05/12/233520
https://hitori-sekai.com/python/error-pyenv/

## MacのApacheでPythonをCGIとして実行する方法
https://www.runoob.com/python/python-cgi.html
https://qiita.com/TSKY/items/b041de0572e6586c889c
macの場合、「ScriptAlias /cgi-bin/ /var/www/cgi-bin/」の設定が必要ないです。
### macの場合、CGIフォルダーは下記となります
/Library/WebServer/CGI-Executables
### macの場合、webなどのフォルダーは下記となります
/Library/WebServer/Documents

## mysqlインストール
https://prog-8.com/docs/mysql-env
### mysql開始/終了、及びログイン、ログアウト
brew services start mysql@5.7
brew services stop mysql@5.7
mysql --user=root --password
exit;
### mysqlのデータベースを作成
https://prog-8.com/docs/mysql-database-setup

## pipをインストール
https://qiita.com/ohbashunsuke/items/e7c673db606a6dced8a6
## mysql-connector-pythonをインストール
pip install mysql-connector-python
## mysql-connector-pythonを使用mysqlを操作
https://qiita.com/valzer0/items/2f27ba98397fa7ff0d74

## djangoインストール
git clone https://github.com/django/django.git

## django設定
cd dgangoフォルダー
sudo python setup.py install
