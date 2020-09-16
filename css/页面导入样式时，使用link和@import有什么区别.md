+ 1.从属关系区别
  - ink属于XHTML标签，不仅可以加载 CSS 文件，还可以定义 RSS、rel 连接属性等。而@import是CSS提供的，只能用于加载CSS;
+ 2.加载顺序区别、
  - 页面被加载的时，link会同时被加载，而@import引用的CSS会等到页面被加载完再加载;

+ 3.兼容性区别
  - 而link是XHTML标签，无兼容问题， import是CSS2.1 提出的，只在IE5以上才能被识别，

+ 4.DOM可控性区别
  - 可以通过 JS 操作 DOM ，插入link标签来改变样式；由于 DOM 方法是基于文档的，无法使用@import的方式插入样式。
+ 5.权重区别
  - link引入的样式权重大于@import引入的样式。