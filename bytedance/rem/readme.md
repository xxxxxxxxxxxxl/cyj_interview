1. 了解所有的单位 
    绝对单位：px  移动物理像素密度
    相对单位:vw/vh em rem 100%   
    css 适配问题 相对我们要适配的机型等比例的缩放
    100%(栅格系统10rem =100vw ,字体大小，行高1.12333%) -> em 是自身字体的等比例(WEUI,麻烦) -> rem(html根元素的字体大小) -> vm/vh(兼容性不行)
    vm/vh  em rem 100%

2. 动态rem 不同的手机，10rem =100vw
3. 布局题：div 垂直居中，左右10px，高度始终为宽度的一半，使用vw/vh来实现