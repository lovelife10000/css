# css3
## 1.水平居中：
- 对于block元素，margin：0 auto；
- 对于inline-block和inline元素，text-align:center


## 2.垂直居中：
- 对于inline-block和inline元素，如果高度是固定的，则line-height:固定高度；如果高度是未知的，可以利用伪元素进行把高度撑高100%，宽度0

- 水平和垂直都有的定位写法：绝对定位，加margin负值（或transform: translate(-50%,-50%);）


##3.弹性盒子
- 对于弹性盒子子元素，可以设置margin:{auto}可以实现水平垂直居中

##占全屏
- 绝对定位加宽度高度100%（或者上下左右0）
