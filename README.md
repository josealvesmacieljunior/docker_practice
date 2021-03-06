aa


本书既适用于具备基础 Linux 知识的 Docker 初学者，也希望可供理解原理和实现的高级用户参考。同时，书中给出的实践案例，可供在进行实际部署时借鉴。前六章为基础内容，供用户理解 Docker 的基本概念和操作；7 ~ 9 章介绍一些高级操作；第 10 章给出典型的应用场景和实践案例；11 ~ 13 章介绍关于 Docker 实现的相关细节技术。后续章节则分别介绍一些相关的热门开源项目。

在线阅读：[GitBook](https://www.gitbook.io/book/yeasy/docker_practice) 或 [DockerPool](http://dockerpool.com/static/books/docker_practice/index.html)。



《[Docker 技术入门与实战](http://item.jd.com/11598400.html)》一书已经正式出版，包含大量第一手实战案例和更为深入的技术剖析，欢迎大家阅读使用。

* [China-Pub](http://product.china-pub.com/3770833)
* [京东图书](http://item.jd.com/11598400.html)
* [当当图书](http://product.dangdang.com/23620853.html)
* [亚马逊图书](http://www.amazon.cn/%E5%9B%BE%E4%B9%A6/dp/B00R5MYI7C/ref=lh_ni_t?ie=UTF8&psc=1&smid=A1AJ19PSB66TGU)

## 主要版本历史
* 0.6: 2015-07-?
    * 补充 Machine 项目
* 0.5: 2015-06-29
    * 添加 Compose 项目

    * 添加 Mesos 项目内容
* 0.4: 2015-05-08
    * 添加 Etcd 项目
    * 添加 Fig 项目
    * 添加 CoreOS 项目
    * 添加 Kubernetes 项目

    * 修正底层实现章节的架构、名字空间、控制组、文件系统、容器格式等内容；
    * 添加对常见仓库和镜像的介绍；
    * 添加 Dockerfile 的介绍；
    * 重新校订中英文混排格式。
    * 修订文字表达。
    * 发布繁体版本分支：zh-Hant。

    * 添加命令查询和资源链接章节；
    * 其它修正。
* 0.1: 2014-09-05
    * 添加基本内容;

## 参加步骤
* 在 GitHub 上 `fork` 到自己的仓库，如 `docker_user/docker_practice`，然后 `clone` 到本地，并设置用户信息。
```
$ git clone git@github.com:docker_user/docker_practice.git
$ cd docker_practice
$ git config user.name "yourname"
$ git config user.email "your email"
```
* 修改代码后提交，并推送到自己的仓库。
```
$ #do some change on the content
$ git commit -am "Fix issue #1: change helo to hello"
$ git push

```
$ git remote add upstream https://github.com/yeasy/docker_practice
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
```
