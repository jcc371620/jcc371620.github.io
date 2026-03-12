1. 开了vpn后，github commit and sync报错 -

解决办法：commit与sync分开执行。先commit，
然后在terminal执行：
git config --global http.proxy http://127.0.0.1:7890
git config --global https.proxy http://127.0.0.1:7890
