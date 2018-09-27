加载vue文件时首先加载的方法是：
```
initMixin(Vue); // 初始化方法
stateMixin(Vue); // 原型上绑定$set、$delete、$watch方法及$data、$props属性
eventsMixin(Vue); // 原型上绑定$on、$once、$off、$emit方法，实现全局的观察者模式，作为事件机制
lifecycleMixin(Vue);
renderMixin(Vue);
```