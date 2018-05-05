[一步步在GitHub上创建博客主页](http://www.pchou.info/ssgithubPage/2013-01-03-build-github-blog-page-01.html)

[Hexo 3.1.1 静态博客搭建指南](http://lovenight.github.io/2015/11/10/Hexo-3-1-1-%E9%9D%99%E6%80%81%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E6%8C%87%E5%8D%97/)


[如何搭建一个独立博客——简明Github Pages与Hexo教程](https://www.jianshu.com/p/05289a4bc8b2)

[使用Github Pages建独立博客](http://beiyuu.com/github-pages)


-------------
[Markdown](https://www.jianshu.com/p/b03a8d7b1719)

[MobaXterm](https://www.cnblogs.com/sjqlwy/p/mobaxterm.html)
Remote environment: Xfce4 desktop

[安装Node.JS](https://linux.cn/article-5766-1.html)
```
./configure
make
sudo make install
```
```
node -v
vim test.js
    console.log("test")
node test.js
```

[安装及使用hexo](http://ibruce.info/2013/11/22/hexo-your-blog/)

[documents](https://hexo.io/docs/setup.html)

[configuration](https://hexo.io/docs/configuration.html)
```
sudo npm install -g hexo
```
```
hexo init <your folder>

or 

cd yourfolder
hexo init
```
```
hexo generate
hexo server
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
```
```
vim _config.yml
    deploy:

        type: git

        repo: https://github.com/zero2up/zero2up.github.io.git

        branch: master


npm install hexo-deployer-git --save

hexo deploy

```
