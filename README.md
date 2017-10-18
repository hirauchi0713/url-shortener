# Google URL Shortener Wrapper

usage

```
$ url-shortener URL
```

* api

	https://developers.google.com/url-shortener/

* service

	https://goo.gl/
	
* curl

	https://curl.haxx.se/

* jq

	https://stedolan.github.io/jq/

example(vim)

```
"
" [http://www.verylong.url/long/long] -> [https://goo.gl/VyUgV6]
"
map <Space>W ci]<C-R>=system("url-shortener "."<C-R>"")<CR><ESC>
```
