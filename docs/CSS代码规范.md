# CSS代码规范

eg:

```
.main {
  height: 100px;
  padding: 0;
  font-family: Arial, sans-serif;
}
.row,
.item,
.member {
  line-height: 10px;
}
/* ---------- */
/*  PRE LOAD  */
/* ---------- */
!大区域注释
/* - ROW 0 -  */
!小区域注释
/*
 * this part will be broken when screen is resize
 * under 560px, need responsive design and write a
 * new rule for it
 */
!多行注释
.post {
  font-family: arial, sans-serif;
  font-size: 12px;
  line-height: 1.5;
}
.img {
  background: url("bg.png");
}
```

1. 使用**2个空格**作为一个缩进层级，不允许 4个空格 或 tab 字符。
2. **选择器**与 `{` 之间必须包含空格。
3. **属性名**与之后的`:`之间不允许空格， `:`与**属性值**之间必须包含空格。
4. **列表型属性值**在单行书写时，`,` 后必须跟一个空格。
5. 当一个CSS规则块包含多个选择器时，每个选择器声明必须独占一行。
6. 属性定义必须另起一行。
7. 属性定义后必须以分号结尾。
8. 在可以使用缩写的情况下，尽量使用属性缩写。
9. 尽可能不使用 `!important` 声明。
