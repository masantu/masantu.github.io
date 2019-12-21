# masantu
用于存放Hexo源目录
## 更新日志
- 2019-12-21
    1. 添加[hexo-hide-posts](https://github.com/printempw/hexo-hide-posts/)隐藏指定文章；
    ```shell
    hidden: true
    ```
    2. 添加[Valine](https://github.com/xCss/Valine)使能评论功能；
    
        TODO: 点击链接位置样式有点丑
- 2019-12-16
    1. 添加[hexo-douban](https://github.com/mythsman/hexo-douban)实现豆瓣页面爬取功能；
        ```shell
        $ hexo douban -h
        Usage: hexo douban
        
        Description:
        Generate pages from douban
        
        Options:
          -b, --books   Generate douban books only
          -g, --games   Generate douban games only
          -m, --movies  Generate douban movies only
        ```
- 2019-12-06
    1. 添加[hexo-tag-aplayer](https://github.com/MoePlayer/hexo-tag-aplayer)实现文章页音乐播放功能；
        ```html
        <meting-js
            auto="https://y.qq.com/n/yqq/song/001RGrEX3ija5X.html">
        </meting-js>
        ```

- 2019-11-22
    1. 添加[hexo-blog-encrypt](https://github.com/MikeCoder/hexo-blog-encrypt)插件实现需要阅读密码访问功能；
    2. 添加[hexo-Admin](https://github.com/jaredly/hexo-admin)插件实现非命令行式写作；
        ```bash
        hexo server -d
        ```
