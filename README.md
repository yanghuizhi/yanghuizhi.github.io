

# [杨会智的博客](yanghuizhi.github.io)

### 强制更新本地git到仓库，（针对 hexo 问题）

``
    git push -f origin master
``

### hexo一键命令：

```bazaar
hexo clean && hexo g && hexo d

此命令有一个弊端，强制覆盖git源代码，所以每次执行的时候都要慎重，建议以下步骤：

hexo clean && hexo g
git add . && git commit -m "update" && git push

``
