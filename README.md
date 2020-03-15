smallest example that i could make work:


``` shell
$ mkdir jamstack-minmimal-test-2
$ pushd jamstack-minmimal-test-2/
$ git init
$ hub create
$ touch index.html
$ e index.html
$ netlify dev -d .
```

