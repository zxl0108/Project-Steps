## **jQuery** **方法**

> jQuery 插件

### **jQuery**插件**

```
jQuery 功能比较有限，想要更复杂的特效效果，可以借助于 jQuery 插件完成。 

注意: 这些插件也是依赖于jQuery来完成的，所以必须要先引入jQuery文件，因此也称为 jQuery 插件。

jQuery插件常用的网站：

1.  jQuery 插件库  http://www.jq22.com/     

2.  jQuery 之家   http://www.htmleaf.com/  

jQuery插件使用步骤：

1.  引入相关文件。（jQuery 文件 和 插件文件）    

2.  复制相关html、css、js (调用插件)。
```

### 图片懒加载或者（BOOTSTRAP插件）

（图片使用延迟加载在可提高网页下载速度。它也能帮助减轻服务器负载）

当我们页面滑动到可视区域，再显示图片。

我们使用jquery 插件库  EasyLazyload。 注意，此时的js引入文件和js调用必须写到 DOM元素（图片）最后面

注意：

​	1、要引入JQuery

​	2、插件JS【js引入文件和js调用必须写到 DOM元素（图片）最后面】

​	3、将图片 src 替换为 data-lazy-src

​	4、调用lazyLoadInit(）

### BOOTSTRAP插件

<https://www.bootcss.com/>

​	1、引入CSS、引入JQ、引入JS

​	2、.container

​	3、复制粘贴。