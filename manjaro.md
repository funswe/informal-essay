# 下载manjaro-deepin
https://osdn.net/projects/manjaro-community/storage/deepin/18.0.2/

# 设置国内的源
```
$ sudo pacman-mirrors -i -c China -m rank //更新镜像排名
$ sudo pacman -Syy //更新数据源
```

## 设置 archlinuxcn 源
修改 /etc/pacman.conf　　=> 末尾添加
```
[archlinuxcn]
SigLevel = Optional TrustedOnly
Server = https://mirrors.tuna.tsinghua.edu.cn/archlinuxcn/$arch
```
```
$ pacman -S archlinuxcn-keyring 
```

# win fonts
```
$ sudo mkfontscale
$ sudo mkfontdir
$ fc-cache
```

# 中文乱码
```bash
$ sudo pacman -S wqy-microhei
```
