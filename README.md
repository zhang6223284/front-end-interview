# 更新 List:

 - 2018.4.14: IndexedDB 技术问题更新
 - 2018.4.01: 框架问题更新


# BAT 要的是什么样的前端实习生？

标签 ： 面试 前端

---

面试季又到了，各位小鲜肉也在着手准备基本的面试、实习。但是，有小鲜肉的思想我确实有点不敢苟同。面试无非就是问一些问题，你能答出来就行，答不出来就 pass。那如果我知道你要问哪些问题，这不就行了吗？感觉这不就是做一场考试吗？

一个学期的课程，我用 7 天学完，题目我都会做，考试分数还比那些学了一个学期的要好得多。那我为什么还要上课呢？现在，侥幸你通过了面试，知道如何做算法题，但在实际工程领域，你这样的人能解决什么问题呢？

年轻人拥有着无限可能大概是这世界上最搞笑的一句话了。本来在这个世界上在某一个领域里做好一件事情都很难的，怎么就无限可能了呢？越是对世界缺少洞见，对自己缺乏了解，越是容易被这句话感动得热泪盈眶。

最近看了一下，基本的面试题目集，发现都是一问一答的形式，这个不是和 7 天速成一模一样了吗？知其然，不知其所以然。那么，我这里也和他们一样，也给大家一份面试题目集，不过，答案并没有写出来，而是在每篇文章里（有些，就直接归纳在下面），你能看懂多少，这个题目你就能解决多少。

> 而面试题目也会持续更新下去

最新的内容，请访问：[front-end-interview][1]

或者也可以关注我的公众号：前端小吉米 ，获得一手的前端预研文章。


![image.png-961.6kB][2]


## 面试问题

### 浏览器内核

- [当输入一个网址时，整个过程是怎样的呢？][3]

- [测速时候，你一般用 Date.now 还是使用 Performance?][4]

- [浏览器渲染原理是什么，了解重排和重绘么？][5]

- [Onload 事件和 DomContentLoaded 事件有什么区别么？][6]


### 缓存协议

- [基本的缓存头协议有哪些？][7]

- [cache-control 和 expires 有什么区别呢？][8]

- [你能结合上面的缓存协议，来组合做一份优化吗？][9]

- 通常像离线存储数据库比如 local storage、IndexedDB 存储有上限值吗？如果超过了，浏览器会怎么处理？

- 在 indexedDB 里面查找数据有几种方式？

- 什么情况下需要更新 IndexedDB？更新 indexedDB 有什么需要注意的么？

### CSS 布局

- [什么叫做盒模型？][10]

- 实现垂直居中办法有哪些呢？

- [网格布局中，设置元素位置方式有哪几种?][11]

- [如何设置行列间的间隔？][12]

### CSS3 动画

- [ translate(X,Y) 是如何对应于矩阵变换的？][13]

等同于 `matrix(1, 0, 0, 1, X, Y); `

- [ matrix 属性值一共有几个？分别代表什么含义？][14]

`matrix(a,b,c,d,e,f);` 等同于 ![此处输入图片的描述][15]

- bezier 曲线有了解么？其 4 个点分别有什么含义？

P0,P1 在一条直线上，P2,P3在一条直线上。其中，P2、P3 x,y 必须在 (0,1) 范围内。而 P0 为 (0,0)，P3 为 (1,1)

![image.png-70.1kB][16]

- 在 keyframe-Animation 中，我们常常使用 bezier 曲线做什么用？

确定每一帧动画的变换速率。一般是有设计给出，确定整体动画的变换速度。需要注意，每一帧动画，都可以设置独立的 `Animation-time-function`。

(CSS 剩下的就是实现效果)



### 浏览器安全

- [基本的浏览器安全问题有哪些？][17]

- [对于 CSRF 来说有什么解决手段吗？][18]


### PWA 技术

- [PWA 中最核心的文件是？][19]

- [SW 的生命周期是什么？][20]

- [Sw 是怎样更新的？][21]

- [PWA 怎么让你的网页打开最快，有什么优化策略？][22]

- [CacheStorage 有大小限制么？如果超出限制，浏览器会怎么处理？][23]



### 前端直播技术

- [有哪些常用的直播协议][24]

- [这些协议的延时性怎么样？][25]

- [前端音视频处理技术用到了什么？][26]

- [MSE 基本架构了解吗？][27]

- [音视频基本概念知道哪些？][28]

- [.mp4 和 MPEG 有区别吗？][29]

- [流处理的 API 有哪些？][30]

- [了解过字节序这个概念吗？][31]

### 安全

- [基本的浏览器安全问题有哪些？][32]

- [对于 CSRF 来说有什么解决手段吗？][33]

### 通信

- [网页有哪些跨域方式的访问呢？][34]

- [如何实现 xhr 和 websocket 的跨域][35]

- [Fetch 的底层架构是怎样的？][36]

- [HTTP2 和 HTTP1.x 比起来有什么优势吗？][37]

- [TCP 三次握手了解吗？][38]


### 算法

- [了解的基本排序算法有哪些？][39]

快排，桶排，冒泡，选择，插入

- [二叉树的前序，中序，后序算法有了解过吗？][40]

- [有了解过 Hash Table 么？他是怎么每次都能有固定长度的 hash 值呢？][41]

通过取余

- [这个 hash 长度有没有讲究？][42]

最好为质数

- [怎么解决 Hash 碰撞呢？][43]

开链法，线性探索，简单来说就是对于相同 hash 增加一个二维数组来记录重复。

- [如何检测括号有没有完整匹配？][44]

通过堆栈来解决


- 一个单词是否是回文？

通过 `split` 拆分字符串，通过数组倒序来实现 (`split('').reverse().join('')`)。

对一个数组进行去重，算法为 O(n)?

利用对象 key 唯一的特性，判断每个数组 val（Obj[val] ）是否一致即可。

- 如何统计字符串中出现次数最多的字符？

同样利用对象 key 的唯一特性来解决。

- [如何模拟一个 getElementsByClassName 的功能？][45]

通过获取整个 tag (`getElementsByTagName("*")`)，然后通过正则匹配（区分单词边界）ClassName 即可。


### 框架问题

- [了解过 redux 和 flux 的区别吗？][46]

redux 比 flux 多了一个中间数据的管理--Reducer

- [React 生命周期了解么？][47]

componentWillMount => render => componentDidMount

- [React 组件更新的声明周期是怎样的？][48]

ComponentWillReciveProps => shouldComponentUpdate => componentWillUpdate => render => componentDidUpdate

 - [能简单描述一下 React 中间件运行方式吗？](https://www.villainhr.com/page/2016/09/11/%E4%BB%8E%E6%BA%90%E7%A0%81%E7%9C%8Bredux%E4%B8%AD%E9%97%B4%E4%BB%B6)

### 全景相关

- [了解过 UV 映射吗？][49]

简单来说就是贴图，用来将 2D 图片映射到 3D 坐标系中。首先确定 2D 的范围，然后将指定 2D 范围图片映射到 3D 坐标中。

- 有了解过如何利用 Three.js 实现一个 UV 映射么？

首先，通过 `MeshPhongMaterial` 将图片加载到纹理空间，利用 `new Vector2` 确定纹理范围。最后，由 `faceVertexUvs` 来执行贴图操作。

- [球面 3D 移动原理知道是什么吗？][50]

简单来说就是球坐标系。通过手机滑动来改变，相机的视角位置。基本的公式为 ![此处输入图片的描述][51]

- [有没有试过陀螺仪来做交互呢？它有几个基本的旋转数据？][52]

有三个旋转角 alpha、beta、gamma。绕着 Z 轴转动的夹角为 alpha，绕着 X 轴转动的夹角为 beta，绕着 Y 轴转动的夹角为 gamma。其通过 `deviceorientation` 事件来提供相应数据。


### webpack 编译工具

- [使用 Webpack 来导出一个 `demo.js` 的库，规定可以通过全局变量、require\import 等方式使用，应该设置哪些属性？][53]

需要设置:

```
libraryTarget:'umd',
library:'demo'
```

- [如何修改通过 `import` 或者 `require` 引用的解析路径？][54]

通过设置 `resolve` 属性值中的 `alias`、`modules` 来完成。


- webpack plugin 和 loader 有什么区别吗？loader、plugin  常用来处理什么？

loader 主要是用来处理原始 sourceCode，比如 js、css、jsx 文件等。它通过函数式编程一层一层的处理。plugin 主要是处理非 Loader 以外的其它辅助文件。


[1]: https://github.com/JimmyVV/front-end-interview
[2]: http://static.zybuluo.com/jimmythr/b0k38n1hjdx6szv1rmnvj5rf/image.png
[3]: https://segmentfault.com/a/1190000004466407
[4]: https://segmentfault.com/a/1190000004466407
[5]: https://segmentfault.com/a/1190000004451497
[6]: https://segmentfault.com/a/1190000004466407
[7]: https://segmentfault.com/a/1190000004486640
[8]: https://segmentfault.com/a/1190000004486640
[9]: https://segmentfault.com/a/1190000004486640
[10]: https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model
[11]: https://www.villainhr.com/page/2016/10/12/%E4%BA%8C%E7%BB%B4%20grid%20%E5%B8%83%E5%B1%80
[12]: https://www.villainhr.com/page/2016/10/12/%E4%BA%8C%E7%BB%B4%20grid%20%E5%B8%83%E5%B1%80
[13]: https://www.villainhr.com/page/2018/03/18/css3%20%E7%9F%A9%E9%98%B5
[14]: https://www.villainhr.com/page/2018/03/18/css3%20%E7%9F%A9%E9%98%B5
[15]: http://image.zhangxinxu.com/image/blog/201206/css-transforms-matrix3.gif
[16]: http://static.zybuluo.com/jimmythr/bhlslwznuhhelo8lyd9qp7fl/image.png
[17]: https://www.villainhr.com/page/2016/07/12/%E7%A1%AE%E4%BF%9D%E4%BD%A0%E7%BD%91%E9%A1%B5%E7%9A%84%E5%AE%89%E5%85%A8#CSRF%20%E6%94%BB%E9%98%B2%E6%88%98
[18]: https://www.villainhr.com/page/2016/07/12/%E7%A1%AE%E4%BF%9D%E4%BD%A0%E7%BD%91%E9%A1%B5%E7%9A%84%E5%AE%89%E5%85%A8#how%20to%20Prevent%20CSRF
[19]: https://www.villainhr.com/page/2017/01/08/Service%20Worker%20%E5%85%A8%E9%9D%A2%E8%BF%9B%E9%98%B6
[20]: https://www.villainhr.com/page/2017/01/08/Service%20Worker%20%E5%85%A8%E9%9D%A2%E8%BF%9B%E9%98%B6
[21]: https://www.villainhr.com/page/2017/01/08/Service%20Worker%20%E5%85%A8%E9%9D%A2%E8%BF%9B%E9%98%B6
[22]: https://www.villainhr.com/page/2017/01/08/Service%20Worker%20%E5%85%A8%E9%9D%A2%E8%BF%9B%E9%98%B6
[23]: https://www.villainhr.com/page/2017/01/08/Service%20Worker%20%E5%85%A8%E9%9D%A2%E8%BF%9B%E9%98%B6
[24]: https://www.villainhr.com/page/2017/08/05/%E4%B8%8D%E5%86%8D%E7%A2%8E%E7%89%87%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%8C%E5%BF%AB%E9%80%9F%E6%8E%8C%E6%8F%A1%20H5%20%E7%9B%B4%E6%92%AD%E6%8A%80%E6%9C%AF
[25]: https://www.villainhr.com/page/2017/08/05/%E4%B8%8D%E5%86%8D%E7%A2%8E%E7%89%87%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%8C%E5%BF%AB%E9%80%9F%E6%8E%8C%E6%8F%A1%20H5%20%E7%9B%B4%E6%92%AD%E6%8A%80%E6%9C%AF
[26]: https://www.villainhr.com/page/2017/08/05/%E4%B8%8D%E5%86%8D%E7%A2%8E%E7%89%87%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%8C%E5%BF%AB%E9%80%9F%E6%8E%8C%E6%8F%A1%20H5%20%E7%9B%B4%E6%92%AD%E6%8A%80%E6%9C%AF#MSE
[27]: https://www.villainhr.com/page/2017/08/05/%E4%B8%8D%E5%86%8D%E7%A2%8E%E7%89%87%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%8C%E5%BF%AB%E9%80%9F%E6%8E%8C%E6%8F%A1%20H5%20%E7%9B%B4%E6%92%AD%E6%8A%80%E6%9C%AF#MSE
[28]: https://www.villainhr.com/page/2017/08/05/%E4%B8%8D%E5%86%8D%E7%A2%8E%E7%89%87%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%8C%E5%BF%AB%E9%80%9F%E6%8E%8C%E6%8F%A1%20H5%20%E7%9B%B4%E6%92%AD%E6%8A%80%E6%9C%AF#%E9%9F%B3%E8%A7%86%E9%A2%91%E5%9F%BA%E6%9C%AC%E6%A6%82%E5%BF%B5
[29]: https://www.villainhr.com/page/2017/03/31/%E5%85%A8%E9%9D%A2%E8%BF%9B%E9%98%B6%20H5%20%E7%9B%B4%E6%92%AD#%E8%A7%86%E9%A2%91%E6%A0%BC%E5%BC%8F%EF%BC%9F%E7%BC%96%E7%A0%81%EF%BC%9F
[30]: https://www.villainhr.com/page/2017/08/05/%E4%B8%8D%E5%86%8D%E7%A2%8E%E7%89%87%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%8C%E5%BF%AB%E9%80%9F%E6%8E%8C%E6%8F%A1%20H5%20%E7%9B%B4%E6%92%AD%E6%8A%80%E6%9C%AF#%E9%9F%B3%E8%A7%86%E9%A2%91%E5%9F%BA%E6%9C%AC%E6%A6%82%E5%BF%B5
[31]: https://www.villainhr.com/page/2017/08/05/%E4%B8%8D%E5%86%8D%E7%A2%8E%E7%89%87%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%8C%E5%BF%AB%E9%80%9F%E6%8E%8C%E6%8F%A1%20H5%20%E7%9B%B4%E6%92%AD%E6%8A%80%E6%9C%AF#%E5%AD%97%E8%8A%82%E5%BA%8F
[32]: https://www.villainhr.com/page/2016/07/12/%E7%A1%AE%E4%BF%9D%E4%BD%A0%E7%BD%91%E9%A1%B5%E7%9A%84%E5%AE%89%E5%85%A8
[33]: https://www.villainhr.com/page/2016/07/12/%E7%A1%AE%E4%BF%9D%E4%BD%A0%E7%BD%91%E9%A1%B5%E7%9A%84%E5%AE%89%E5%85%A8#CSRF%20%E6%94%BB%E9%98%B2%E6%88%9
[34]: https://www.villainhr.com/page/2016/05/18/%E9%80%9A%E4%BF%A1%E6%96%B9%E5%BC%8F%E8%BF%9B%E9%98%B6#CORS%E4%B8%AD%E7%9A%84withCredentials
[35]: https://www.villainhr.com/page/2016/09/25/%E5%89%8D%E7%AB%AF%20fetch%20%E9%80%9A%E4%BF%A1
[36]: https://www.villainhr.com/page/2016/09/25/%E5%89%8D%E7%AB%AF%20fetch%20%E9%80%9A%E4%BF%A1
[37]: https://www.villainhr.com/page/2016/09/17/HTTP2%E5%8D%B3%E6%9C%AA%E6%9D%A5
[38]: https://www.villainhr.com/page/2016/07/19/%E8%AE%A9%E4%BD%A0%E5%8D%87%E7%BA%A7%E7%9A%84%E7%BD%91%E7%BB%9C%E7%9F%A5%E8%AF%86#What%E2%80%99s%20TCP%203%E6%AC%A1%E6%8F%A1%E6%89%8B
[39]: https://www.villainhr.com/page/2016/06/18/%E6%8E%92%E5%BA%8F%E7%AE%97%E6%B3%95#%E5%BF%AB%E9%80%9F%E6%8E%92%E5%BA%8F%28quick%20sort%29
[40]: https://www.villainhr.com/page/2016/06/09/%E4%BA%8C%E5%8F%89%E6%A0%91
[41]: https://www.villainhr.com/page/2016/06/04/%E6%95%A3%E5%88%97%E8%A1%A8#Building%20a%20Hash%20Table
[42]: https://www.villainhr.com/page/2016/06/04/%E6%95%A3%E5%88%97%E8%A1%A8#Building%20a%20Hash%20Table
[43]: https://www.villainhr.com/page/2016/06/04/%E6%95%A3%E5%88%97%E8%A1%A8#Collision%20resolution
[44]: https://www.villainhr.com/page/2016/06/24/%E6%B5%85%E8%B0%88%E6%8B%AC%E5%8F%B7%E5%8C%B9%E9%85%8D
[45]: http://www.jackpu.com/qian-duan-mian-shi-zhong-de-chang-jian-de-suan-fa-wen-ti/
[46]: https://www.villainhr.com/page/2016/09/02/redux%20%E6%8E%A2%E6%9E%90
[47]: https://www.villainhr.com/page/2016/07/17/React%E8%BF%9B%E9%98%B6
[48]: https://www.villainhr.com/page/2016/07/17/React%E8%BF%9B%E9%98%B6
[49]: https://www.villainhr.com/page/2018/01/03/%E7%8E%B0%E5%9C%A8%E5%81%9A%20Web%20%E5%85%A8%E6%99%AF%E5%90%88%E9%80%82%E5%90%97%EF%BC%9F#UV%20%E6%98%A0%E5%B0%84
[50]: https://www.villainhr.com/page/2018/01/03/%E7%8E%B0%E5%9C%A8%E5%81%9A%20Web%20%E5%85%A8%E6%99%AF%E5%90%88%E9%80%82%E5%90%97%EF%BC%9F#3D%20%E7%A7%BB%E5%8A%A8%E5%8E%9F%E7%90%86
[51]: http://static.zybuluo.com/jimmythr/0ver0z35g3b32nme859iisti/image.png
[52]: https://www.villainhr.com/page/2017/12/20/orientation%20%E9%99%80%E8%9E%BA%E4%BB%AA%20API
[53]: https://www.villainhr.com/page/2017/10/27/%E7%9C%8B%E5%95%A5%E5%8F%8C%E6%8B%B1%E9%97%A8%EF%BC%8C%E6%9D%A5%E5%AD%A6%20webpack%203%E5%95%8A#module%20%E7%BC%96%E8%AF%91%E8%AE%BE%E7%BD%AE
[54]: https://www.villainhr.com/page/2017/10/27/%E7%9C%8B%E5%95%A5%E5%8F%8C%E6%8B%B1%E9%97%A8%EF%BC%8C%E6%9D%A5%E5%AD%A6%20webpack%203%E5%95%8A#resolve%20%E6%A8%A1%E5%9D%97%E8%A7%A3%E6%9E%90%E8%B7%AF%E5%BE%84
