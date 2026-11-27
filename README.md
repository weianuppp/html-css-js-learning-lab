# html-css-js-learning-lab

Web 编程技术实验代码，按实验报告编号整理。

| 实验 | 主题 | 原目录 | 整理后的目录 |
| --- | --- | --- | --- |
| 1 | 学工网基础页面制作 | `web1` | `01-basic-student-affairs-page/` |
| 2 | 鲜花网站与盒子模型 | `web5` | `02-flower-shop-box-model/` |
| 3 | 学工网语义化布局 | `web8` | `03-semantic-student-affairs-page/` |
| 4 | 二级导航制作 | `web10` | `04-secondary-navigation/` |
| 5 | Flexbox 导航 | `web12` | `05-flexbox-navigation/` |
| 6 | CSS Grid 网格布局 | `web13/expanding.html` | `06-css-grid-layout/` |

每个实验使用相同的资源结构：

```text
experiment-name/
├── index.html
├── styles.css      # 使用外部样式表的实验
└── assets/         # 图片、图标等素材
```

运行任意实验时，在根目录启动本地静态服务器，再打开对应目录：

```bash
python3 -m http.server 8000
```

例如访问：

```text
http://localhost:8000/02-flower-shop-box-model/
```

也可以直接使用 VS Code 的 Live Server 打开各目录中的 `index.html`。
