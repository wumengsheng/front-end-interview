### CSS相关问题  
#### CSS 选择符有哪些？哪些属性可以继承？优先级算法如何计算？ CSS3新增伪类有那些？  
1.id选择器（ # myid）  
2.类选择器（.myclassname）  
3.标签选择器（div, h1, p）  
4.相邻选择器（h1 + p）  
5.子选择器（ul > li）  
6.后代选择器（li a）  
7.通配符选择器（ * ）  
8.属性选择器（a[rel = "external"]）  
9.伪类选择器（a: hover, li:nth-child）  
可继承的样式： font-size font-family color, text-indent;  

不可继承的样式：border padding margin width height ;  

优先级就近原则，同权重情况下样式定义最近者为准;  

载入样式以最后载入的定位为准;  

优先级为:  
!important >  id > class > tag    

important 比 内联优先级高,但内联比 id 要高  
CSS3新增伪类举例：  
p:first-of-type 选择属于其父元素的首个 `<p>` 元素的每个 `<p>` 元素。  
p:last-of-type  选择属于其父元素的最后 `<p>` 元素的每个 `<p>` 元素。  
p:only-of-type  选择属于其父元素唯一的 `<p>` 元素的每个 `<p>` 元素。  
p:only-child    选择属于其父元素的唯一子元素的每个 `<p>` 元素。  
p:nth-child(2)  选择属于其父元素的第二个子元素的每个 `<p>` 元素。  
:enabled  :disabled 控制表单控件的禁用状态。  
:checked        单选框或复选框被选中。  
