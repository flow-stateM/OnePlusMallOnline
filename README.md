#技术栈
vue vue-cli vuex vue-router vue-YDUI(UI) MockHttp(模拟数据) es6 ajax(axios) 
#设计灵感
一加移动端商城
#实现内容（将要）
美好的阅览体验（文字初次加载上浮动画，图片随着滚动宽度变化动画），商城基本要素（商品列表，商品详情，购物车）

用节流函数解决滚动触发次数过多可能导致卡问题
实现超过距离固定顶部需要了解mounted和created的区别
设计动画交互时候应该禁止触发事件冒泡
实现文字第一次出现上浮需要判断其距离可视区顶部的距离是不是小于一个屏幕的距离
实现多个文字在差异时间上浮需要transition-group
img引用方式 静态资源动态获取需要import 再设置url
设置动画时使用到位移或者translate需要给外层一个overflow:hidden，否则会影响布局
顶部下拉菜单在出现时候返回顶部
computed函数不能带参,且第一次判断的时机是beforecreated和created之间，不能用于判断是否登录（因为永远返回值都是undefined）也就是说用于初始化的所需属性需要在created中执行

设置动画的javascript钩子必须要设置定时器（异步）  暂时没有理解原因




