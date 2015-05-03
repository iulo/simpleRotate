# simpleRotate
移动端转动插件

## usage

```
var play = new Rotate({
            targetEle : document.getElementById('J-pointer')  , //目标元素
            duration: 6000, //过渡时间
            // tranProperty: , //动画类型
            // endAngle: 7600 //终止角度
            // resetAngle: , //重置角度
            callback: function(data){
                alert(data.id);
            }
        });
```

```
                    var data;
                    data.id = Math.floor( Math.random()*9+1 ); // 随机产生数据测试
                    play.setEndAngle(data.id*36 + 7200); //设置转角 7200为默认转20圈
                    play.resetAni();
                    play.startAni(data);
```
