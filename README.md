
支持两种主题模版：
1. 模版一：hugo-orbit-theme 
```
git checkout master

在config.toml,设置baseurl:baseurl = "https://it-boyer.github.io/iMe/"
publishdir = "docs" 发布目录，指向github的本地仓库

hugo -t hugo-orbit-theme
git add .
git push origin master

//修改githubpage：切换master-->docs 
//浏览网页：https://it-boyer.github.io/iMe
```

2. 模版二：almeida-cv
```
git checkout main

在config.toml,设置baseurl:baseurl = "https://it-boyer.github.io/iMe/"
publishdir = "docs" 发布目录，指向github的本地仓库

hugo -t almeida-cv
git add .
git push origin main

//修改githubpage：切换main-->docs 
//浏览网页：https://it-boyer.github.io/iMe
```

