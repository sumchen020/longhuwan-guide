# 龙湖湾景区智慧导览系统

<p align="center">
  <img src="assets/hero_1280x720.jpg" alt="龙湖湾景区" width="100%" style="max-width:800px;border-radius:12px;"/>
</p>

<p align="center">
  <strong>千年顺昌 · 大圣祖地</strong><br>
  一个基于 HTML/CSS/JS 的景区智慧导览单页网站
</p>

<p align="center">
  <a href="#功能特性">功能特性</a> •
  <a href="#在线预览">在线预览</a> •
  <a href="#项目结构">项目结构</a> •
  <a href="#快速开始">快速开始</a> •
  <a href="#技术栈">技术栈</a>
</p>

---

## 功能特性

- **网站首屏**：全屏景区背景图 + 主题标语，支持一键开启导览
- **景区概况**：介绍龙湖湾"一街三轴四坊九巷"布局，展示核心运营数据
- **智慧地图**：SVG 交互式地图，点击 9 个景点标记可查看详细介绍与开放时间
- **景点导览**：6 大景点卡片展示，支持按"文化体验 / 自然风光 / 美食购物"分类筛选
- **路线推荐**：
  - 半日精华游（3.5 小时）
  - 全日深度游（8 小时）
  - 夜游体验游（4 小时）
- **文化体验**：顺昌灌蛋、陶瓷烧制、绒花发簪、大圣文化四大非遗介绍
- **服务设施**：游客中心、停车场、母婴室、医疗急救等 8 项便民服务
- **响应式布局**：完美适配手机、平板、桌面端

```

## 项目结构

```
longhuwan-guide/
├── index.html      # 主页面（单页应用入口）
├── README.md                 # 项目说明文档
├── LICENSE                   # 开源许可证
├── .gitignore                # Git 忽略配置
├── assets/                   # 图片素材目录
│   ├── hero_1280x720.jpg     # 英雄区背景图
│   ├── street_1024x576.jpg   # 古街景点图
│   ├── lake_1024x576.jpg     # 湖景景点图
│   ├── temple_1024x576.jpg   #  temple 景点图
│   └── culture_1024x576.jpg  # 文化体验图
└── _shared/                  # 共享资源目录
    ├── fonts/                # 本地字体文件
    │   ├── IBMPlexSerif-Regular.ttf
    │   ├── IBMPlexSerif-Bold.ttf
    │   ├── Outfit-Regular.ttf
    │   └── Outfit-Bold.ttf
    └── js/
        └── echarts.min.js    # ECharts 图表库
```

## 技术栈

| 技术 | 说明 |
|------|------|
| HTML5 | 语义化标签构建页面结构 |
| CSS3 | Flexbox / Grid 布局、CSS 变量、动画过渡 |
| JavaScript | 原生 JS（无框架），实现地图交互、筛选、标签切换等功能 |
| ECharts | 数据可视化库（已本地引入，预留扩展） |
| SVG | 手绘景区互动地图 |

## 设计规范

- **主色调**：`#1a5f4a`（深绿）—— 自然山水
- **辅助色**：`#c9a55c`（金色）—— 传统文化
- **背景色**：`#f8f6f1`（暖白）—— 纸张质感
- **字体**：
  - 标题：IBMPlexSerif
  - 正文：Outfit + PingFang SC 回退

## 浏览器兼容性

- Chrome / Edge（推荐）
- Firefox
- Safari
- 移动端浏览器（iOS Safari、Chrome Mobile）

## 许可证

本项目基于 [MIT](LICENSE) 许可证开源。

## 致谢

- 景区信息参考：[东南网 - 顺昌县龙湖湾城市客厅](http://np.fjsen.com/wap/2025-04/03/content_31876611.htm)
- 字体来源：[Google Fonts](https://fonts.google.com/)（本地托管）
- 图表库：[Apache ECharts](https://echarts.apache.org/)

---

<p align="center">
  Made with ❤️ for 顺昌县龙湖湾城市客厅
</p>
