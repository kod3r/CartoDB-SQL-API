SQL API for cartodb.com
========================
 
Provides a concurrent event driven interface for running SQL queries against the cartoDB postgres database. Users are authenticated over oAuth. Also provides ability to make public "SELECT" only calls.

usage
------
``` bash
node cluster.js [developement,test,production]
```

tests
------
``` bash
make test
```


core requirements
-------------
* pg_bouncer
* postgres
* redis
* node v0.4.8+

node.js dependencies
---------------------
* npm

then to install dependencies from package.json:

``` npm install .```

