Randolphcarter
==============
Randolphcarter is searcher in Python based on Pagerank algorithm, Neural networks, and so on.
The name 'Randolph Carter' has its root in [the works of H.P.Lovecraft](http://en.wikipedia.org/wiki/Randolph_Carter)

Usage
=======
```python
import randolphcarter
import nn
mynn=nn.searchnet('nn.db')
mynn.maketables()
carter=randolphcarter('searchindex.db')
carter.query(unicode('Ultimate','utf-8'))
```

Prerequisite
========
- [nyarlathotep](https://github.com/zedoul/nyarlathotep)

