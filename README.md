# 图床

 [![cdn](https://img.shields.io/badge/cdn-jsdelivr-brightgreen)](https://www.jsdelivr.com/)  [![github](https://img.shields.io/badge/repos-github-orange)](https://github.com)   [![picgo](https://img.shields.io/badge/tool-PicGo-blue)](https://github.com/Molunerfinn/picgo/releases) 

###### 描述：三步实现一个图片秒开、免费的图床

**第一步**：github设置

1.创建一个repository

![repository](https://cdn.jsdelivr.net/gh/liouoth/pic_repos/blog/20200927184531.jpg)

2.生成一个token

点击github用户头像，路径：Settings/Developer settings ,点击 generate token

![repository](https://cdn.jsdelivr.net/gh/liouoth/pic_repos/blog/20200927184537.jpg)



note随意填写，勾选repo，点击Generate token

![repository](https://cdn.jsdelivr.net/gh/liouoth/pic_repos/blog/20200927184542.jpg)



复制这个token（否则就没了！之后不会再次显示！）

![repository](https://cdn.jsdelivr.net/gh/liouoth/pic_repos/blog/20200927184644.jpg)



第二步：配置工具

1.下载picgo

github下载地址： [PicGo](https://github.com/Molunerfinn/picgo/releases)

下载完成后，直接安装

2.设置github图床

仓库名以及存储路径注意。**eg:我这里存储路径设置blog/,将会在git仓库根目录创建blog文件夹**

![repository](https://cdn.jsdelivr.net/gh/liouoth/pic_repos/blog/20200927184732.jpg)

3.直接在上传区，开始上传吧！文件链接可以在相册中，点击按钮复制！



第三步：配置自定义域名（第二步中的设定自定义域名，用户图片的访问）

> hsdelivr是一个免费开源的cdn，可以直接访问github中的文件，速度非常快
>
> 格式：https://cdn.jsdelivr.net/gh/ github用户名 / 你的仓库名



现在就能够直接访问啦！速度杠杠的！

![repository](https://cdn.jsdelivr.net/gh/liouoth/pic_repos/blog/20200927184738.jpg)