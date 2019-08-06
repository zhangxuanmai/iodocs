# JSX

JSX 就是一种将 JavaScript 和 HTML 结合起来的一种语法。

## 语法特点

- 由元素组成，类似 html 标签
- 内部可以使用 { } 放置任何有效的 JavaScript 表达式
- 属性的名称使用 camelCase（小驼峰命名）, 属性值可以用字符串，或者 { } 插入JS表达式
- 为便于阅读，可以将 JSX 拆分为多行（外部用括号包裹）

下面是一段代码示例：

```jsx
const name = 'tom'
const url = 'xxx.png'

const element1 = (
  <h1>hello, { name }</h1>
)

const element2 = (
  <img className="active" src="xxx.png"></img>
  <img src={ url }></img>
)

const element3 = (
  <button onClick={ handleMethos }></button>
)
```

## 基本单元

在 JSX 中，元素是最基本单元，我们的组件也是由一个个元素构成而来。

```jsx
// element 是一个元素
const element = <h1>hello, world</h1>
```