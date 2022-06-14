# linux
常用命令
fuser -v /dev/nvidia* | grep -o -E '[0-9]+' | xargs kill -9 ##一键杀死僵死进程
