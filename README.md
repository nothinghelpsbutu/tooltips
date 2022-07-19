# tooltips

纯css工具提示 bubbles-tooltips [查看效果](https://ipfs.io/ipfs/QmQ7EmTbETESV3uMvkFn8kVxeH57LmiKtqd9vuL6LsPd2h)

## 常规使用方法

直接在页面中引用`tooltips.min.css`

```html

<link rel="stylesheet" href="tooltips.min.css">
<span data-tooltips="我是提示" data-tooltips-pos="up">tooltips</span>
```

## 在页面中使用

```html

<button data-tooltips="top" class="tooltips-top">top</button>
<button data-tooltips="bottom" class="tooltips-bottom">bottom</button>
<button data-tooltips="left" class="tooltips-left">left</button>
<button data-tooltips="right" class="tooltips-right">right</button>
<button data-tooltips="bottom-left" class="tooltips-bottom-left">bottom-left</button>
<button data-tooltips="bottom-right" class="tooltips-bottom-right">bottom-right</button>
<button data-tooltips="top-right" class="tooltips-top-right">top-right</button>
<button data-tooltips="top-left" class="tooltips-top-left">top-left</button>

<button class="tooltips-top  tooltips-small" data-tooltips="small工具提示">Small</button>
<button class="tooltips-top  tooltips-medium" data-tooltips="medium工具提示!!!!!!!">Medium</button>
<button class="tooltips-top  tooltips-large" data-tooltips="large工具提示!!!!!!!">Large</button>
<button class="tooltips-bottom  tooltips-always" data-tooltips="...还可以这样提示">还可以这样提示</button>

```

## 新增背景颜色提示

```html

<button data-tooltips="error tooltips" class="tooltips-top tooltips-error">error</button>
<button data-tooltips="warning tooltips" class="tooltips-top tooltips-warning">warning</button>
<button data-tooltips="info tooltips" class="tooltips-top tooltips-info">info</button>
<button data-tooltips="success tooltips" class="tooltips-top tooltips-success">top</button>
```


