showmemory
==========

Show memory usage in current process.

[![NPM](https://nodei.co/npm/showmemory.png?stars&downloads)](https://nodei.co/npm/showmemory/) [![NPM](https://nodei.co/npm-dl/showmemory.png)](https://nodei.co/npm/showmemory/)

Installation
============

```bash
$ npm install showmemory
```

Usage
=====

```javascript
var showMemory = require('showmemory');
showMemory();
```

output:
```bash
Process: heapTotal 5.88 MB heapUsed 2.25 MB rss 12.86 MB
---------------------------------------------------------
Process: heapTotal 5.88 MB heapUsed 2.26 MB rss 12.87 MB
---------------------------------------------------------
Process: heapTotal 5.88 MB heapUsed 2.26 MB rss 12.87 MB
---------------------------------------------------------
Process: heapTotal 5.88 MB heapUsed 2.27 MB rss 12.88 MB
---------------------------------------------------------
```

when you use showMemory, the process will never stop untill you use ctrl + c.
