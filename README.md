### 多级联动组件

### 功能
- [x] 全局检索
- [x] 层级检索


### usage

```js
new Select2({
    childNameList:[],                               // 可能的子元素键盘值
    targetNameList:[],                              // 当前节点储存原俗名
    select: document.querySelector(".select2"),     // 当前select元素
    level: ['事项分类','费用分类','费用名称'],        // 等级名称
    data,
})
```

### 依赖环境
- JavaScript
- es6
- chrome 65+



### issues
- [x] 屏幕自动上滚
- [ ] 没选完的时候自动清空选项。。禁止选一半的东西发上去
- [ ] 给原来的 select  赋值id
- [ ] 备注信息