# Vue购物车项目

这是一个基于Vue.js的购物车示例项目，实现了商品浏览、添加购物车、订单管理和支付流程等功能。

## 功能特点

- 商品分类与列表展示
- 商品规格选择
- 购物车管理（添加、修改数量、清空）
- 订单创建与管理
- 15分钟订单倒计时功能
- 支付流程（支付宝/微信支付选择）
- 响应式设计，适配移动端

## 技术栈

- Vue 3 (Composition API)
- Vant UI 组件库
- HTML5 / CSS3
- localStorage 本地存储

## 页面说明

项目包含三个主要页面：

1. **主页面 (main.html)**
   - 商品分类与列表
   - 购物车功能
   - 未完成订单提醒

2. **订单详情页 (order-detail.html)**
   - 订单商品列表
   - 订单金额计算
   - 配送信息
   - 倒计时显示

3. **支付页面 (pay.html)**
   - 支付方式选择（支付宝/微信）
   - 支付二维码展示
   - 倒计时显示

## 项目预览

你可以通过以下链接预览项目：

- **项目主页：** [https://mhxy13867806343.github.io/vue-shopping-cart/main.html](https://mhxy13867806343.github.io/vue-shopping-cart/main.html)
- **订单详情页：** [https://mhxy13867806343.github.io/vue-shopping-cart/order-detail.html](https://mhxy13867806343.github.io/vue-shopping-cart/order-detail.html)
- **支付页面：** [https://mhxy13867806343.github.io/vue-shopping-cart/pay.html](https://mhxy13867806343.github.io/vue-shopping-cart/pay.html)

项目代码仓库：[https://github.com/mhxy13867806343/vue-shopping-cart](https://github.com/mhxy13867806343/vue-shopping-cart)

## 本地运行

1. 克隆仓库
```bash
git clone https://github.com/mhxy13867806343/vue-shopping-cart.git
```

2. 进入项目目录
```bash
cd vue-shopping-cart
```

3. 使用本地服务器运行项目（例如使用VS Code的Live Server插件）

## 项目结构

```
vue-Shopping-Cart/
├── main.html           # 主页面
├── order-detail.html   # 订单详情页
├── pay.html            # 支付页面
├── static/             # 静态资源
│   ├── main.css        # 主页面样式
│   ├── order-detail.css # 订单详情页样式
│   └── pay.css         # 支付页面样式
├── pub/                # 第三方库
│   ├── vue.global.js   # Vue.js
│   ├── vant.min.js     # Vant UI组件库
│   └── vant.min.css    # Vant UI样式
└── img/                # 图片资源
```

## 功能流程

1. 在主页面浏览并选择商品
2. 添加商品到购物车
3. 点击"去结算"进入订单详情页
4. 在订单详情页确认订单并点击"去支付"
5. 在支付页面选择支付方式并完成支付
6. 支付成功后返回主页

## 注意事项

- 订单有15分钟的有效期，超时将自动取消
- 支付功能为模拟实现，不会发生实际交易

## 贡献

欢迎提交问题和改进建议！

## 许可

MIT
