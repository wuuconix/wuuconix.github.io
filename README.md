## 2021.1.7号更新

博客直接放github pages上了！

因为写博客是在本地的wsl上，写完build好以后还要手动scp上传到服务器上，有些麻烦。

利用github的自定义域名功能将 [https://wuuconix.github.io](https://wuuconix.github.io) 转到了 [https://wuuconix.link](https://wuuconix.link)

本来是想用github action 自动部署的，只要上传源码就能够自动build更新pages。

但是用的那个action 没报错，显示成功，但是 pages仓库根本没有收到commit。

目前还是用的 hexo自带的deploy插件。

之后希望能够直接用github action自动部署，只需要上传源码即可，本地都不需要build。

## 2021.1.8号更新

成功实现github actions自动部署，效果见 [https://wuuconix.link/2022/01/08/actions/](https://wuuconix.link/2022/01/08/actions/)
