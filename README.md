# Picker
> 公司项目开发中经常用到的一个组件, 起先也用到了如Mint UI等第三方组件库, 但是产品需求复杂, picker滑动的时间段也是从后端获取, 进行计算的, 所以自己结合不同的业务需求, 也为了复习巩固一下原生js,将这个组件抽离开源出来

**总结:**
- 无依赖, 纯原生js面向对象的方式去实现
- 整个组件的js只用到了300多行实现
- 滑动动画流畅, 在安卓,ios下未出现兼容问题
- 适合单独使用,或者结合mvvm框架,如 vue
- 自定义滑动列表项,可以根据不同业务需求填充
- 增加了示例调用代码
