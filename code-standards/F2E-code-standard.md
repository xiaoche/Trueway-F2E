# 中威科技前端开发规范

## 1. 总则
此为前端开发团队遵循和约定的代码书写规范，意在提高代码的规范性和可维护性。  
此规范为参考规范，不全是硬性要求，统一团队编码规范和风格。让所有代码都是有规可循的，并且能够得到沉淀，减少重复劳动。

## 2. 基础规范

### 2.1 静态文件夹结构

assets
├── css
│   ├── 
│   └── 
├── js
│   ├── 
│   └── 
├── images
│   ├── 
│   └── 

### 2.2 命名规范


## 3. HTML规范

### 3.1 DOCTYPE

```html
<!DOCTYPE html>
```

### 3.2 Meta

### 3.3 嵌套规则

```html
/*推荐层级*/
<div class="mod">
	<div class="hd"></div>
	<div class="bd"></div>
	<div class="ft"></div>
</div>
```
* 禁止出现内联元素嵌套块级元素
* 语义化标签，有序排列用<ol>


### 3.4 标准模板

````html
<!DOCTYPE html>
<!--Html5 doctype-->
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
<!--IE浏览器默认以最高版本渲染-->
<meta name="renderer" content="webkit" />
<!--双核360浏览器以极速模式渲染-->
````

### 3.5 浏览器兼容

IE8禁止Quirks Mode，以浏览器最高版本渲染页面。

```html
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
```

360浏览器以极速模式渲染页面

```html
<meta name="renderer" content="webkit" /> 
```

原则上兼容IE8以上版本，页面加浏览器版本判断，低于IE8给出一个友情弹出层，提示用户升级浏览器或者选择其他浏览器。


### 3.6 其他
* 避免使用`style="xxx:xxx"`内联样式
* `<img>`标签默认格式`<img src="xxx.jpg" alt="文字" />`
* `<a>`标签默认格式`<a href="###" title="文字" >xxx</a>`

## 4. CSS规范

### 4.1 CSS文件夹

### 4.2 SASS使用规范

sass
├── core
│   ├── 
│   └── 
├── libs
│   ├── 
│   ├── 
│   └── 
├── biz
│   ├── 
├── pages
│   ├── 

### 4.3 CSS命名规范

### 4.3 CSS注释规范

### 4.4	CSS属性顺序

### 4.5 CSS嵌套规则

### 4.6 CSS格式

## 5. JS规范

### 5.1 JS文件夹结构

### 5.2 JS命名规范

### 5.3	JS细化规范

## 6. 基础组件库

## 7. 前端效率工具

