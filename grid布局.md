<style>
.container{
	display:grid;
	grid-template-columns:100px 100px 100px;
	grid-template-rows:100px 100px 100px;
	grid-gap:10px;
}
.item {
  font-size: 4em;
  text-align: center;
  border: 1px solid #e5e4e9; 
  display:inline-grid;
  place-content:center;
}
.item-1{
	grid-row:1 / 3;
	grid-column: 1 / 3;	
}
.item-4{
	grid-row:2 / 4;
}
</style>


# Grid布局
======================================
## 介绍
* 网格布局（Grid）是最强大的 CSS 布局方案。它将网页划分成一个个网格，可以任意组合不同的网格，做出各种各样的布局。

## 入门
* 行、列、单元格、网格线

<div class="container">
	<div class="item item-1">1</div>
	<div class="item item-2">2</div>
	<div class="item item-3">3</div>
	<div class="item item-4">4</div>
	<div class="item item-5">5</div>
</div>

## 容器属性
* display、grid-template-columns、grid-template-rows、grid-gap、place-items、place-content 

## 项目属性
* grid-column、grid-row、grid-area、place-self  