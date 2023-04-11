# SimpleWebNavigation
这是一个基于PHP给个人使用的网址导航，所有链接均可以在txt文件中添加与删除而不需要修改代码

原作者`https://github.com/KrunkZhou/SimpleWebNavigation`，二次修改作者`https://github.com/hanumio/nav`，本程序基于二次修改版本。



## 演示

![demo](https://raw.githubusercontent.com/uselibrary/SimpleWebNavigation/main/demo.jpg)



## 使用方法

### 安装
下载后上传到php空间。
### 修改标题、简介
编辑`index.php`

### 链接编辑 `links.txt`

格式：
```
box
分类名称
fontawesome名称
链接名
链接地址
链接名
链接地址
.....
.....
endbox
```
### 左侧导航栏编辑`nav.txt` 
```
链接名称
链接地址
```

支持添加`#`锚点链接
```
学习探索
#学习探索
```

### 卡片分类图标

分类图片采用[fontawesome](https://fontawesome.com)，复制`<i class="fas fa-music"></i>`中的`fas fa-music`到links.txt。
### 

修改 `data.txt` 就能修改导航卡片

格式：
```
box
分类名称
iconfont名称
链接名
链接地址
链接名
链接地址
.....
.....
endbox
```

举个栗子：
```
box
常用
iconfont icon-tool
Get it on GitHub
https://github.com/KrunkZhou/SimpleWebNavigation
Maps
https://www.google.ca/maps/
Translate
https://translate.google.com/
GitHub
https://github.com/
BiliBili
https://www.bilibili.com/
endbox
```

