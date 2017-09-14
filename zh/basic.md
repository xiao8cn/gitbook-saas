#项目基本规范

***

####文件夹命名规范

######目前的src 目录结构如下
```js
+---assets                        // 样式放置
|   +---common                      // 公用scss
|   +---fonts                       // 字体
|   \---theme                       // 皮肤
+---mock                            // mock库
+---pages                           // 页面
|   \---home                        // home 页面
+---partial                         // 页面引用的vue
|   \---cms-brand
+---templates                       // 公共模板
|   \---standard                    // 通用模板
\---widgets                         // 组件库
    +---form                        // form 表单类
    \---item                        // 商品item 类
```

> 所有的文件夹命名都为横线分割全小写的形式

***

####js命名规范

######目前的目录下的js命名如下

```js
├─checkout
│      checkout.js
│      checkout.scss
│
├─consult
│      consult.js
│
├─coupon
│      coupon-list.js
│      coupon-list.scss
│
├─forget
│      forget.js
│      forget.scss
│
├─home
│      home.html
│      home.js
│      home.scss
```

> 所有的js命名都为横线分割全小写的形式

***

####Vue文件命名规范

######目前的目录下的Vue命名如下

```js
│
├─saas
│      SaasAdv.vue
│      SaasScreen.vue
│      SaasTags.vue
│
├─saas-shop-cart
│      SaasShopCart.vue
│
├─saas-tags
│      SaasTags.vue
│
├─simple-footer
│      SimpleFooter.vue
│
├─simple-header
│      SimpleHeader.vue
│
└─top-nav
        TopNav.vue
```

> 所有的Vue文件命名都为首字母大写驼峰命名