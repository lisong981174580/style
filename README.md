# style
##### 不定宽高元素垂直方向上的居中的两种方法
######(1)、父元素设置
```
display: flex;
justify-content: center;
align-items: center;

```

###### (2)、子元素设置
```
 position: absolute;
 left: 50%;
 top:50%;
 transform: translate(-50%,-50%);
 
 ```
