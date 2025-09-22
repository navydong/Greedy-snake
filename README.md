# Greedy Snake Game 贪吃蛇游戏

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Development Status](https://img.shields.io/badge/status-in%20development-yellow.svg)]()

一个基于现代技术栈开发的经典贪吃蛇游戏实现。

A classic Snake game implementation built with modern technology stack.

## 🎮 游戏特性 / Game Features

- 🐍 经典贪吃蛇游戏玩法 / Classic Snake gameplay
- 🎯 多种难度级别 / Multiple difficulty levels  
- 🏆 积分排行榜 / Score leaderboard
- 🎨 现代化UI设计 / Modern UI design
- 📱 响应式布局，支持移动端 / Responsive design for mobile
- ⌨️ 键盘和触屏双重控制 / Keyboard and touch controls
- 🔊 音效支持 / Sound effects support
- 💾 游戏进度保存 / Game progress saving

## 🚀 快速开始 / Quick Start

### 环境要求 / Prerequisites

- Node.js 16+ 
- 现代浏览器 / Modern web browser

### 安装和运行 / Installation & Running

```bash
# 克隆项目 / Clone the repository
git clone https://github.com/navydong/Greedy-snake.git

# 进入项目目录 / Navigate to project directory
cd Greedy-snake

# 安装依赖 / Install dependencies
npm install

# 启动开发服务器 / Start development server
npm run dev

# 构建生产版本 / Build for production
npm run build
```

## 🎯 游戏玩法 / Gameplay

1. **移动控制 / Movement Control**
   - 使用方向键 ↑↓←→ 或 WASD 控制蛇的移动
   - Use arrow keys ↑↓←→ or WASD to control snake movement
   - 移动端支持滑动手势 / Mobile supports swipe gestures

2. **游戏规则 / Game Rules**
   - 🍎 吃掉食物增加分数和蛇身长度 / Eat food to increase score and snake length
   - 💥 撞墙或撞到自己身体游戏结束 / Game ends when hitting walls or snake body
   - ⭐ 收集特殊道具获得额外奖励 / Collect special items for bonus points

3. **难度等级 / Difficulty Levels**
   - 简单 / Easy: 慢速移动，适合新手 / Slow speed, perfect for beginners
   - 普通 / Normal: 中等速度，经典体验 / Medium speed, classic experience  
   - 困难 / Hard: 快速移动，挑战高手 / Fast speed, for experts
   - 极限 / Extreme: 超高速度，终极挑战 / Ultra-fast speed, ultimate challenge

## 🛠️ 技术栈 / Tech Stack

- **前端 / Frontend**: HTML5 Canvas, CSS3, JavaScript ES6+
- **构建工具 / Build Tools**: Webpack/Vite
- **样式 / Styling**: SCSS/CSS3
- **音频 / Audio**: Web Audio API
- **存储 / Storage**: LocalStorage
- **部署 / Deployment**: GitHub Pages

## 📁 项目结构 / Project Structure

```
Greedy-snake/
├── src/                    # 源代码 / Source code
│   ├── game/              # 游戏核心逻辑 / Game core logic
│   │   ├── Snake.js       # 蛇类 / Snake class
│   │   ├── Food.js        # 食物类 / Food class
│   │   ├── Game.js        # 游戏主类 / Main game class
│   │   └── GameEngine.js  # 游戏引擎 / Game engine
│   ├── ui/                # 用户界面 / User interface
│   │   ├── Menu.js        # 菜单界面 / Menu interface
│   │   ├── HUD.js         # 游戏HUD / Game HUD
│   │   └── Settings.js    # 设置界面 / Settings interface
│   ├── assets/            # 资源文件 / Assets
│   │   ├── images/        # 图片 / Images
│   │   ├── sounds/        # 音效 / Sound effects
│   │   └── styles/        # 样式 / Styles
│   └── utils/             # 工具函数 / Utility functions
├── dist/                  # 构建输出 / Build output
├── docs/                  # 文档 / Documentation
├── tests/                 # 测试文件 / Test files
├── index.html             # 入口文件 / Entry file
├── package.json           # 项目配置 / Project configuration
└── README.md              # 项目说明 / Project documentation
```

## 🎨 截图预览 / Screenshots

*游戏截图将在开发完成后添加 / Screenshots will be added after development*

## 🚧 开发计划 / Development Roadmap

### Phase 1: 基础功能 / Basic Features
- [ ] 游戏核心逻辑实现 / Core game logic implementation
- [ ] 基础UI界面 / Basic UI interface
- [ ] 碰撞检测系统 / Collision detection system
- [ ] 分数系统 / Scoring system

### Phase 2: 增强功能 / Enhanced Features  
- [ ] 多难度级别 / Multiple difficulty levels
- [ ] 音效系统 / Sound system
- [ ] 本地存储 / Local storage
- [ ] 排行榜功能 / Leaderboard functionality

### Phase 3: 高级功能 / Advanced Features
- [ ] 移动端适配 / Mobile adaptation
- [ ] 特殊道具系统 / Special items system
- [ ] 皮肤/主题系统 / Skins/themes system
- [ ] 多人对战模式 / Multiplayer mode

## 🤝 贡献指南 / Contributing

欢迎贡献代码！请遵循以下步骤：
Contributions are welcome! Please follow these steps:

1. Fork 本仓库 / Fork the repository
2. 创建功能分支 / Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 提交更改 / Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 / Push to the branch (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request / Open a Pull Request

### 开发规范 / Development Standards
- 使用 ESLint 进行代码规范检查 / Use ESLint for code linting
- 遵循现有的代码风格 / Follow existing code style
- 为新功能添加测试 / Add tests for new features
- 更新相关文档 / Update relevant documentation

## 📝 许可证 / License

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 作者 / Author

**navydong** - *Initial work* - [navydong](https://github.com/navydong)

## 🙏 致谢 / Acknowledgments

- 感谢所有为经典贪吃蛇游戏做出贡献的开发者们
- Thanks to all developers who contributed to the classic Snake game
- 灵感来源于经典的诺基亚贪吃蛇游戏
- Inspired by the classic Nokia Snake game

---

⭐ 如果这个项目对你有帮助，请给个星标！ / If this project helps you, please give it a star!

🐛 发现问题？请提交 [Issue](https://github.com/navydong/Greedy-snake/issues)
🐛 Found a bug? Please submit an [Issue](https://github.com/navydong/Greedy-snake/issues)
