# Crawler_revenue
Korea Univ Paper Crawler Project

# Usage
Scrapy 모듈을 사용한 크롤러 작성
## Environment
```
python 3.7.8
scrapy
selenium
```
## Stage
```
1) install pip
2) command : pip install pip env (with powershell)
3) git clone [this project]
4) command : pipenv shell(in project folder)
5) command : pipenv install(install packages)
6) command : cd crawler
7) command : scrapy crawl sites --nolog (sites is spider name)
```
* illegals.db is first db for get connection sites
* sites_connection.db is result db from scrapy crawler