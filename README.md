# scrapy-at-a-glance

<https://docs.scrapy.org/en/latest/intro/overview.html>

Steps:

1. Init git repo
1. install virtualenv `virtualenv venv`
1. activate virtualenv `source venv/Scripts/activate` (on linux | can use git bash console on windows)
1. create requirements.txt file and add
    1. scrapy
    1. -
1. and install it with `pip install -r requirements.txt`
1. create file `quotes_spider.py`
1. run the file using `scrapy runspider quotes_spider.py -o quotes.jsonl`
    1. this will create the file `quotes.jsonl`
1. END
