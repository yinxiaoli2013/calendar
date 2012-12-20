# 月例

- order: 2

------------

首先需要引入样式文件，默认提供了一个 simple 主题。

````html
<link rel="stylesheet" href="../src/css/month.css" />
````

## There is nothing to do

````html
<input id="month-nothing" type="text" />
````

````javascript
seajs.use('month-calendar', function(Month) {
    var month = new Month({});
    month.show();
});
````