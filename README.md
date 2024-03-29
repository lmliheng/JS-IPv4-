## IPv4查询小站
demo网址：http://ip.yunduanjianzhan.cn/
![image](https://github.com/lmliheng/JS-IPv4-/blob/main/md1.png)
![image](https://github.com/lmliheng/JS-IPv4-/blob/main/md2.png)
#### 技术栈：原生JS
原理：接入API，上传数据至页面
#### 站长目的
（1）用来练习API接口格式规范性
（2）按钮优化：
1.基本样式；
2.使用伪元素 ::before 为按钮制作模糊边缘效果：在按钮的第一个或最后一个子元素上使用伪元素创建一个与按钮相同形状且带有模糊滤镜的效果层，并在鼠标悬停时显示。
3.定义动画效果 glow：通过 background-size: 400% 和 @keyframes glow 实现了按钮背景颜色渐变流动的效果。根据不同的按钮（第一个或最后一个），在鼠标悬停时应用不同的线性渐变背景色。
4.响应式设计：当屏幕宽度小于或等于767px时，.container 类的内边距会减小至10px，以适应移动端屏幕。
（3）实现容器的模糊：利用div:before伪元素创建一个覆盖在原div上的模糊边框效果。通过负值定位和增加尺寸，使伪元素超出实际div的大小，并应用内阴影和模糊滤镜，从而实现一种独特的视觉效果。同时，原div设置了overflow: hidden属性，确保了在呈现特效的同时，不会因伪元素超出部分而影响到div内的主要内容布局
