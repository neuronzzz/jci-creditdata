# jci-creditdata

### ref
* scapy
  * https://docs.scrapy.org/en/latest/intro/tutorial.html

* qcc code
  * Python爬企查查网站数据的爬虫代码如何写？ - 张同学的回答 - 知乎
    * https://www.zhihu.com/question/46234054/answer/2925292345
      * todos
        * 如何正确的找到element的XPATH
          * 超过一定时间，提示再登录
        * 打开新的标签页，需要切换新的标签页
        * 拿到信息之后，关闭标签页
  * tbd
    * django issue
      * https://stackoverflow.com/questions/70319606/importerror-cannot-import-name-url-from-django-conf-urls-after-upgrading-to
        * pip install django==3.2.10

### scrapy cmd
```bash
scrapy crawl quotes
```

```bash
scrapy shell 'https://quotes.toscrape.com/page/1/'
```

```bash
view(response)
```