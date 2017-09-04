# flex
弹性布局flxbox
## 盒子的兼容性写法
> display: -webkit-flex;  /* 新版本语法: Chrome 21+ */

    display: flex;          /* 新版本语法: Opera 12.1, Firefox 22+ */
  
    display: -webkit-box;   /* 老版本语法: Safari, iOS, Android browser, older WebKit browsers. */
    
    display: -moz-box;      /* 老版本语法: Firefox (buggy) */
    
    display: -ms-flexbox;   /* 混合版本语法: IE 10 */   
    
    
## 子元素的兼容性写法
>   -webkit-flex: 1;        /* Chrome */  

    -ms-flex: 1             /* IE 10 */  
    
    flex: 1;                /* NEW, Spec - Opera 12.1, Firefox 20+ */
    
    -webkit-box-flex: 1     /* OLD - iOS 6-, Safari 3.1-6 */  
    
    -moz-box-flex: 1;       /* OLD - Firefox 19- */       
