anti-qqphishing
===============

### 26.1.2015 Update
A new and quick method is established using [cURL] instead. The basic command of curl post request is:

``` bash
curl -b csrftoken=ASAPL9SSI0EOdUJPD9Yk6xrNOF79M7Am -d "name=curl_test" http://127.0.0.1:8000/rango/add_category/
```
For more details see [cURL tutorial on emulating a web browser].

### Introduction
This project will aim to defend from tons of fake QQ related phishing websites.

I'm using [Scrapy] to initialize the web crawler framework.

[Scrapy]:http://scrapy.org
[cURL]:http://curl.haxx.se
[cURL tutorial on emulating a web browser]:http://curl.haxx.se/docs/httpscripting.html
