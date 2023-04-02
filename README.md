# Conky Configuration

## 效果预览图

![1680426506445](image/README/1680426506445.png)

## 操作步骤

### 一、下载Conky

#### Arch系
```bash
sudo pacman -S conky
```
---
### 二、克隆文件
下载好后，将conky.conf 移至 ~/.config/conky/下，（记得将原来的做备份)
```bash
mv ~/.config/conky/conky.conf ~/.config/conky/conky.conf.bak
git clone https://github.com/xjimlinx/Conky_configs.git
cd Conky_configs
cp ./conky.conf ~/.config/conky/conky.conf
```
