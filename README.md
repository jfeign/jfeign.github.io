# note
[https://www.cnblogs.com/liuxianan/p/build-blog-website-by-hexo-github.html](https://www.cnblogs.com/liuxianan/p/build-blog-website-by-hexo-github.html)

* Hexo 的 generate 命令，将 Hexo 编译生成 HTML 代码，命令如下：
`hexo g`

* 看到输出结果里面包含了 js、css、font 等内容，并发现他们都处在了项目根目录下的 public 文件夹下面了。
然后我们利用 Hexo 提供的 serve 命令把博客在本地运行起来，命令如下：
`hexo s`

常见命令

hexo new "postName" #新建文章 hexo n
hexo new page "pageName" #新建页面
hexo generate #生成静态页面至public目录  缩写:hexo g
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server） hexo s
hexo deploy #部署到GitHub  hexo d
hexo help  # 查看帮助
hexo version  #查看Hexo的版本

```
组合命令：
```bash
hexo s -g #生成并本地预览
hexo d -g #生成并上传
```



```bash
nvm version                         
v8.16.1
nvm list 
nvm use 16.15.0  



写博客
定位到我们的hexo根目录，执行命令：

hexo new 'my-first-blog'

2022-05-24
最后删除了 environments 才恢复
主题地址: https://github.com/blinkfox
