# swfl / snowfall - Website www.griend.eu

A static website which is uploaded to an Azure Static Webapp with
Github actions on every commit.


If `python3` is installed, you can view it [locally](http://localhost:8000) by executing:

```shell
$ python3 -m http.server -d src/site
Serving HTTP on :: port 8000 (http://[::]:8000/) ...
::1 - - [21/Mar/2022 14:27:24] "GET / HTTP/1.1" 200 -
::1 - - [21/Mar/2022 14:27:24] "GET /css/style.css HTTP/1.1" 200 -
```
