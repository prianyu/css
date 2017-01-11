#border属性的特点以及实际的应用场景

border属性是在实际的应用中使用频率比较高的一个属性。利用border属性的一些特征以及表现方式，可以在实现一些比较常见的效果（如等高布局，上下固定内容滚动布局），利用css3新增的属性值（如使用图片填充边框）可以实现一些更复杂的效果。

1. border的特点   
	（1）border可以分开写，也可以拆分成具体的属性写。如
	```css
		
		.border {
			border: 1px solid #f00;
		}
		
		.border {
			border-width: 1px;
			border-style: solid;
			border-color: #f00;
		}
	```   
	以上两种写法均指定了1px宽度大小的红色实线
	
	
	
	
