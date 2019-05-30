hello vs code
=============

下载于19年5月28日
----------------

#这是一级标题
##这是二级标题
###这是三级标题
####这是四级标题
#####这是五级标题
######这是六级标题

文本本来是不能换行的，<br>
但是这样就可以了。\<br>

http://au.9you.com

        两个tab效果

        这是一段文本
        还没结束
        依旧没有结束

文字高亮`1左边的点`

[劲舞团](http://au.9you.com "鼠标悬停显示文字")

* 列表
* 1

* 子节列表
    * 1
        * 2

> 数据结构
>> 1
>>> 2
>>>> 3

![图片引入](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559207854607&di=8bdec6ecf7826be10e6eae3ec527dba1&imgtype=0&src=http%3A%2F%2Fhbimg.b0.upaiyun.com%2F9678463fe652730cd52d1285d8874782f428b0ed1f9db-JevoUv_fw658 "这是一张图")

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>iview example</title>
    <link rel="stylesheet" type="text/css" href="http://unpkg.com/iview/dist/styles/iview.css">
    <script type="text/javascript" src="http://vuejs.org/js/vue.min.js"></script>
    <script type="text/javascript" src="http://unpkg.com/iview/dist/iview.min.js"></script>
</head>
<body>
<div id="app">
    <i-button @click="show">Click me!</i-button>
    <Modal v-model="visible" title="Welcome">Welcome to iView</Modal>
</div>
<script>
    new Vue({
        el: '#app',
        data: {
            visible: false
        },
        methods: {
            show: function () {
                this.visible = true;
            }
        }
    })
  </script>
</body>
</html>
```

```
$ npm install iview --save //注释
```

```
import Vue from 'vue';
import iView from 'iview';
import locale from 'iview/dist/locale/en-US';

Vue.use(iView, { locale });
```





