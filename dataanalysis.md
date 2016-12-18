## Data Analysis with dat

Dat can help us avoid the tedious task of find, organizing, and retrieving data. So we can directly start analyze data within jupyter notebook.

1. Install [iJavascript](https://github.com/n-riesco/ijavascript)

    npm install -g ijavascript

2. write a `package.json`, install `hyperspark` as dependency.

    npm init -y
    npm i --save hyperspark

3. Start doing research on data inside any dat archive

```javascript
    const spark = require('hyperspark')

    var rdd = spark(<ARCHIVE_KEY>)
    # dat-transform provides spark-rdd like API for you
```

![demo](https://github.com/poga/dat-ipynb-demo/blob/master/demo.png)

