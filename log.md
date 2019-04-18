# 100 Days Of Code - Log

### Day1  2019-04-16:  
**今天的进步**: 开始重新学习前端基础知识，复习了HTML标签和浏览器缓存相关内容，做了4道闭包相关题目.

**思考:** 闭包需要重新复习，达到不用想就能解释的很清楚的目的和一个题目能否用闭包一眼就能判断的标准，还有欠缺，模块设计模式就是IIFE，即立即执行函数表达式，闭包中的变量会一直存在，除非主动消毁闭包的引用。

**项目链接:** [JS 闭包](https://github.com/youyi2016/JS-Closures/blob/master/closures.js)


### Day2  2019-04-17:  
**今天的进步**: 工作中练习，尝试使用grid布局改变以往的flex布局，实现自适应内容的长度布局（因为加班会没有太多自己时间练习）.

**思考:** 通过grid的gird-template-columns、gird-template-rows可以快速实现指定行指定列的布局，然后再使用grid-column-start、grid-column-end指定元素的起始布局位置，可以调整元素的对齐方式。对于具有二维特征的布局可以考虑使用grid来快速实现，如果需要自适应内容长度增大宽度的元素的布局，如果使用flex布局实现自适应元素内容长度来增大元素宽度的布局需求，除了给父级元素设置flex布局，还要考虑给每个flex子元素设置属性自适应剩下空间。使用grid只需要关心元素要如何划分，要分多少行多少列，从哪条线开始排列，每一行，每一列的高度、宽度为多少，grid更像是一种在全局视角的位置在写布局，从整体到细节，样式写起来比flex更灵活，书写样式的时候，思路上感觉更清晰。

**项目链接:** [grid布局小练习](https://codepen.io/youyi2016-the-encoder/pen/NmyLxx?editors=1100)


### Day3  2019-04-18:  
**今天的进步**: 手写动画，css中实现动画有2种，transition和animation，transition只有一个起始状态和一个结束状态；而animation通过keyframes可以设置多帧动画.

**思考:** 什么时候该用transition什么时候该用animation？transition强调的是单一动画属性的效果，例如渐显等动效，animation强调的是多种动画属性的结合，可以给元素设置多帧动画动画效果更好。animation可以实现transition的动画效果，transition可以看作animation的子集，但是animation比transition更耗性能，所以一般transition能实现的动效不用animation实现。animation当动效结束会自动回到最初状态，而transition会停留在最终设置的结束状态。

**项目链接:** [CSS动画](https://codepen.io/youyi2016-the-encoder/pen/NmYLYN)



