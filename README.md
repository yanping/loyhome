loyhome
=======

落园的博客主题

十月二日 尝试用http://prose.io 做在线编辑器

要注意的问题：

- 文本文件用utf-8格式
- 最好用unix下的换行符
- YAML模板里的每个key后面接一个冒号，然后要加*空格*，记住，一定要有*空格*！然后才是value
- 如果把该目录下的文件都上传到你的github主目录，比如username.github.com上，就把`_config.yml`里的baseurl这项用`#`注释掉。
- 如果把该目录下的文件都上传到名为repo-name的github代码库中，要正确查看网页就要在`_config.yml`文件中修改baseurl的值，也就是改为
```
baseurl: repo-name
```

