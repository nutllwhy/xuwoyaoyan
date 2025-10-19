# 赵露思穿搭合集网站 - 许我耀眼

这是一个展示电视剧《许我耀眼》中赵露思角色穿搭的精美网站。

## 功能特点

- ✨ 现代化、响应式设计
- 📱 完美支持移动端和桌面端
- 🎨 优雅的动画和过渡效果
- 🔍 按集数分类展示穿搭
- 📦 详细的单品信息（品牌、商品名、价格）

## 文件结构

```
xuwoyaoyan/
├── index.html          # 主页面
├── style.css           # 样式文件
├── data.js            # 穿搭数据
├── script.js          # 交互脚本
├── README.md          # 说明文档
└── pic/               # 图片文件夹
    ├── IMG_0829.jpg
    ├── IMG_0830.jpg
    ├── IMG_0831.JPG
    ├── IMG_0832.JPG
    ├── IMG_0833.JPG
    ├── IMG_0834.JPG
    ├── IMG_0835.JPG
    ├── IMG_0836.JPG
    ├── IMG_0837.JPG
    └── IMG_0838.JPG
```

## 如何使用

### 方法一：直接打开（推荐）
直接双击 `index.html` 文件即可在浏览器中打开网站。

### 方法二：使用本地服务器
如果遇到跨域问题，可以使用本地服务器：

```bash
# 使用 Python 3
python3 -m http.server 8000

# 或使用 Python 2
python -m SimpleHTTPServer 8000

# 或使用 Node.js (需要先安装 http-server)
npx http-server -p 8000
```

然后在浏览器中访问：`http://localhost:8000`

## 内容说明

### 第1集穿搭（6套）
1. 米色优雅套装 - JORAY、BVLGARI、Hermes等
2. 清新商务风 - ClinkClunk、Tissot等
3. 甜美粉色裙装 - PINKO、Versace、JIMMY CHOO等
4. 温柔米色两件套 - Luna7xi、kiss cat等
5. 黑色干练套装 - Stella Vespertina等
6. 休闲工装风 - TeenieWeenie、demi et demi等

### 第2集穿搭（4套）
1. 浪漫粉色连衣裙 - MaisonWester、VERSACE等
2. 运动休闲套装 - PINKO、JORAY等
3. 帅气军绿外套 - AIVEI、Courreges等
4. 纯白仙女套装 - CLEON、OUBIYABI等

## 技术栈

- HTML5
- CSS3（使用 CSS Grid 和 Flexbox）
- 原生 JavaScript（无需任何框架）

## 浏览器兼容性

- ✅ Chrome/Edge (最新版本)
- ✅ Firefox (最新版本)
- ✅ Safari (最新版本)
- ✅ 移动端浏览器

## 自定义修改

### 添加新的穿搭
编辑 `data.js` 文件，在对应的集数数组中添加新的穿搭对象：

```javascript
{
    id: 11,
    title: '穿搭标题',
    image: 'pic/图片文件名.jpg',
    items: [
        { brand: '品牌名', name: '商品名', price: '¥价格' }
    ]
}
```

### 修改颜色主题
编辑 `style.css` 文件中的 CSS 变量：

```css
:root {
    --primary-color: #d4a373;    /* 主色调 */
    --secondary-color: #8b7355;  /* 次色调 */
    --text-dark: #2c2c2c;        /* 深色文字 */
    /* ... */
}
```

## 许可证

仅供个人学习和欣赏使用。

---

创建日期：2025年10月14日


