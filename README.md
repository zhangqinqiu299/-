# 考试倒计时小工具

一个简洁实用的考试倒计时单页应用，帮助用户追踪考试时间。

## 🎯 功能特性

### Main 分支（基础版）
- 用户可输入考试日期和时间
- 实时显示剩余天数、小时、分钟、秒
- 支持暂停/重置倒计时功能

### 分支 A - feature/style-beautify（样式美化版）
- 🌈 渐变动态背景效果
- ✨ 粒子漂浮动画效果
- 🎨 优化字体、颜色、间距
- 📱 响应式设计，适配不同屏幕尺寸
- 💫 倒计时数字脉冲动画效果

### 分支 B - feature/logic-optimize（逻辑优化版）
- ⚡ 优化倒计时逻辑，解决时间误差问题
- 🎴 数字翻牌式动态切换效果
- 🔔 倒计时结束提醒音效
- 📢 倒计时结束弹窗提示

## 🛠️ 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)

## 🚀 快速开始

### 克隆仓库

```bash
git clone https://github.com/zhangqinqiu299/-.git
cd -
```

### 切换到不同分支

**基础版（main）：**
```bash
git checkout main
```

**样式美化版（分支A）：**
```bash
git checkout feature/style-beautify
```

**逻辑优化版（分支B）：**
```bash
git checkout feature/logic-optimize
```

### 运行项目

直接在浏览器中打开 `index.html` 文件即可运行，无需额外配置或服务器。

## 📖 使用方法

1. 在输入框中选择考试日期
2. 输入考试时间（小时和分钟）
3. 点击「开始倒计时」按钮
4. 倒计时将实时显示，可以随时暂停或重置

## 📁 项目结构

```
exam-countdown/
├── index.html    # 主页面
└── README.md     # 项目说明
```

## 🌿 分支说明

| 分支名称 | 功能描述 |
|---------|---------|
| main | 基础倒计时功能 |
| feature/style-beautify | 样式美化 + 渐变背景 + 粒子效果 |
| feature/logic-optimize | 逻辑优化 + 翻牌效果 + 音效提醒 |

## 📝 开发说明

### 创建新功能分支

```bash
git checkout main
git checkout -b feature/your-feature-name
```

### 提交更改

```bash
git add .
git commit -m "描述你的更改"
git push origin feature/your-feature-name
```

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

⭐ 如果这个项目对你有帮助，请给个 Star！