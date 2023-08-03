# HtmlStudy

## 标题

+ h1

+ h2

+ h3

+ h4

+ h5

+ h6

## 段落

p

## 换行

br

## 水平线

hr

## 文本格式化标签

+ b

+ i

+ u

+ s

+ strong

+ em

+ ins

+ del

## 图片

+ img

+ src

+ alt

+ width

+ height

+ title

## 音频

+ audio

+ src

+ controls

+ autoplay（大多浏览器不支持）

+ loop

## 视频

+ video

+ src

+ controls

+ autoplay（配合muted）

+ loop

## 超链接

+ a

+ href

+ target

+ _self

+ _blank

## 列表

+ ul

+ ol

+ li

+ dl

+ dt

+ dd

## 表格

+ table

+ tr

+ td

+ th

+ border

+ caption

+ thead

+ tbody

+ tfoot

+ rowspan

+ colspan

## 表单

+ input

+ type

+ text

+ password

+ radio

+ checkbox

+ name

+ file

+ multiple

+ button

+ submit

+ reset

+ value

+ placeholder

+ checked

+ form

+ select

+ option

+ selected

+ textarea

+ label

+ id

+ for

## 语义化标签

+ div

+ span

## 字符实体

`&nbsp;`

<hr>

# CSSStudy

## 选择器

+ 标签选择器  

+ `.`+类选择器

+ `#`+id选择器

+ `*`：通选选择器

## 文字基本样式

+ font-size(xxx px)

+ font-weight
  
  + normal
  
  + bold

+ font-style
  
  + [normal]()
  
  + italic

+ font-family
  
  + sans-serif

## font复合属性

style weight size/line-height family

## 文本缩进

+ text-indent

## 水平对齐方式

+ text-align

+ center

+ left

+ right

## 文本修饰线

+ text-decoration

+ underline

+ overline

+ line-through

+ none

## 行高

+ line-height

## 标签居中

+ `margin: 0 auto`

## 选择器

### 后代选择器

`选择器1 选择器2`

### 子代选择器（只能是儿子）

`选择器1>选择器2`

### 并集

`选择器1,选择器2`

### 交集

`选择器1.选择器2`

### 伪类（鼠标悬停效果）

`选择器:hover`

## 背景

### 背景色

background-color

### 背景图

+ background-image

+ url

### 背景位置

+ background-position

+ left

+ center

+ right

+ top

+ bottom

### 背景平铺

+ background-repeat

+ no-repeat

+ repeat-x

+ repeat-y

+ repeat

## 显示模式转换

+ display

+ block

+ inline-block

## 边框

+ border

+ solid

+ dashed

+ dotted

## 内边距

+ padding

## 内减模式

+ box-sizing

+ border-box

## 清除样式

```css
* {
    margin: 0;
    padding : 0;
}
```

## 版心居中

+ `margin : 0 auto`
