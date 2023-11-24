# employment.py
该文件抓取的是智联招聘网站的招聘信息，可以根据需要设置输入搜索关键词和查找页数，就会得到结果，生成相应的文件“{keyword}zhilian”，
项目中的AIzhilian.csv、javazhilian以及pythonzhilian就是生成的示例文件。
# employment2.py
通过驱动模拟自动控制浏览器搜索boss直聘网页上的相关信息，有关搜索关键词也是在代码上硬编码，不过目前有些问题只实现了一页，该程序爬取
得到的结果文件也是生成在同目录下，文明名为“boss_{运行时的日期}”
