## 安装
```shell
npm install hnotify
```

## 使用
```javascript
var nwNotify = require('hnotify');

//通知停留时间
nwNotify.setConfig({
    displayTime: 60000
});

nwNotify.notify({ title: '通知', text: '内容', image: 'who.png', onClickFunc: function(){
    alert(1);
}});
```