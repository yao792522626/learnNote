# 前端学习的一些碎碎念

### 一. 手写常规 JS 代码笔记

- [手写 Object.create]
  **思路：将存入的对象作为原型**

  1. 创建一个空对象
  2. 设置原型链
  3. 返回新对象

  ```ts
     fucntion create(obj) {
     function F() {}
     F.prototype = obj;
     return new F();
     }
  ```

- [手写 instanceof]
- [手写 call]
- [手写 apply]
- [手写 bind]
- [手写 new 操作符]
- [手写 promise]
- [手写防抖函数]
- [手写节流函数]
- [手写类型判断函数]
- [手写深拷贝函数]
- [手写数组去重函数]
- [手写数组扁平化函数]
