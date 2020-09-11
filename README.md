# script
script 

## vbox
```
curl -k https://raw.githubusercontent.com/ydj317/script/master/vbox-init -o ~/vbox-init
curl -k https://raw.githubusercontent.com/ydj317/script/master/vbox-network -o ~/vbox-network
curl -k https://raw.githubusercontent.com/ydj317/script/master/vbox-addon -o ~/vbox-addon

chmod +x vbox-*
```
```
1. vbox-init
 - ./vbox-init
2. vbox-network
 - # 添加第二个网卡 host-only
 - ./vbox-network
3. vbox-addon
 - # 安装增强功能
 - ./vbox-addon
```
```
挂载共享文件夹
mount -f vboxfs www /mnt/www
```
