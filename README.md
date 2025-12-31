# my-rime

## 安装

``` bash
brew install --cask squirrel
cd ~
git clone --depth=1 https://github.com/rime/plum
cd plum
bash rime-install iDvel/rime-ice:others/recipes/full
bash rime-install wangyuehong/my-rime
```

## 升级

``` bash
cd ~/plum
bash rime-install plum                               # 升级 plum
bash rime-install iDvel/rime-ice:others/recipes/full # 升级 rime-ice
bash rime-install wangyuehong/my-rime                # 应用个人配置
```
