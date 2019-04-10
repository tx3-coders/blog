## RSS 文件规则

个人blog更新时,无论通过什么方式搭建的,需维护一个xxx_rss.xml文件(存在公共repo).
xxx_rss.xml需包含以下内容:
- title: 标题
- link: 文章链接
- description: 文章简介
- pubDate:文章发表时间

### example:
``` xml
<?xml version="1.0" encoding="utf-8"?>

<rss version="2.0">
  <channel>
    <item>
      <title>这里是文章标题</title>
      <link>https://sixgodzhang.github.io/article/miscellaneous/%E5%AD%97%E7%AC%A6%E7%BC%96%E7%A0%81/</link>
      <description>测试条目1</description>
    </item>
 </channel>
</rss>
```