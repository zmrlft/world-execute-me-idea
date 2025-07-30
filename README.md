# world.execute(me);

[English](#english) | [中文](#chinese)

## 🚀 Quick Start with Docker

The fastest way to run this project:

```bash
docker run -d -p 8080:80 --name world-execute-me-app zmrlft/world-execute-me:v0.1.0
```

Then visit: http://localhost:8080

To stop the container:
```bash
docker stop world-execute-me-app
docker rm world-execute-me-app
```

---

## English

### About This Project

This is an interactive web experience that simulates the IntelliJ IDEA IDE interface while playing the song "world.execute(me);" by momocashew. The project creates an immersive coding environment that synchronizes with the music, featuring:

- **IntelliJ IDEA Interface Simulation**: Complete IDE interface with project explorer, code editor, terminal, and toolbar
- **Synchronized Visual Effects**: Code typing, terminal output, and visual effects that match the song's timeline
- **Interactive Elements**: Run, debug, and stop buttons that control the experience
- **Error Notifications**: Dynamic error popups during the execution phase
- **Git Integration Simulation**: Realistic git push progress with rainbow cat progress bar

### About the Song

**Title**: world.execute(me);  
**Artist**: momocashew  
**Album**: Miracle Milk  

The title is written in Java syntax (though this syntax is common in most object-oriented languages), meaning "execute the member function 'execute' of the 'world' object with the argument 'me'". In plain language, it translates to "World, execute me."

On May 19, 2022, a Key Ingredient version of the song was released and included in the Key Ingredient album.

### Features

- 🎵 **Audio Synchronization**: Perfect timing with the original song
- 💻 **IDE Simulation**: Realistic IntelliJ IDEA interface
- 🎨 **Visual Effects**: Dynamic code typing, error notifications, and animations
- 🐱 **Rainbow Cat Progress**: Git push simulation with animated progress bar
- ⚠️ **Error Spam**: Multiple error notifications during execution phase
- 🎮 **Interactive Controls**: Play, pause, and stop functionality

### How to Use

1. Open `index.html` in a web browser
2. Click on the IntelliJ IDEA launch screen to start
3. Use the run button to start the experience
4. Watch as the code editor types along with the song
5. Experience the synchronized visual effects and animations

### Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies
- **Audio File**: Requires `world-execute-me.wav` in the same directory
- **Responsive Design**: Works on desktop and mobile devices
- **Cross-browser Compatible**: Tested on modern browsers

### Docker Deployment

#### Quick Start with Docker

```bash
# Pull and run the Docker image
docker run -d -p 8080:80 yourusername/world-execute-me

# Or use docker-compose
docker-compose up -d
```

#### Build and Deploy

```bash
# Build the image
docker build -t world-execute-me .

# Run locally
docker run -d -p 8080:80 world-execute-me

# Push to Docker Hub (replace 'yourusername' with your Docker Hub username)
docker tag world-execute-me yourusername/world-execute-me
docker push yourusername/world-execute-me
```

#### Using the Deployment Script

**Linux/macOS:**
```bash
# Build and push to Docker Hub
./deploy.sh yourusername

# Build only (no push)
./deploy.sh
```

**Windows:**
```cmd
# Build and push to Docker Hub
deploy.bat yourusername

# Build only (no push)
deploy.bat
```

---

## Chinese

## 🚀 Docker 快速开始

运行此项目的最快方式：

```bash
docker run -d -p 8080:80 --name world-execute-me-app zmrlft/world-execute-me:v0.1.0
```

然后访问：http://localhost:8080

停止容器：
```bash
docker stop world-execute-me-app
docker rm world-execute-me-app
```

### 关于这个项目

这是一个交互式网页体验，模拟IntelliJ IDEA IDE界面，同时播放momocashew的歌曲"world.execute(me);"。该项目创建了一个与音乐同步的沉浸式编程环境，具有以下特色：

- **IntelliJ IDEA界面模拟**：完整的IDE界面，包含项目浏览器、代码编辑器、终端和工具栏
- **同步视觉效果**：与歌曲时间轴匹配的代码输入、终端输出和视觉效果
- **交互元素**：控制体验的运行、调试和停止按钮
- **错误通知**：执行阶段的动态错误弹窗
- **Git集成模拟**：带有彩虹猫进度条的真实git推送进度

### 关于歌曲

**标题**：world.execute(me);  
**演唱者**：momocashew  
**专辑**：Miracle Milk  

标题实为Java语言（不过大部分的面向对象语言写法皆如此），意为执行「world」对象的成员函数「execute」，实参为「me」，翻译成现实语言就是「世界，执行处决我」。

2022年5月19日，发布了该曲的Key Ingredient版本，并收录在Key Ingredient专辑中。

### 功能特色

- 🎵 **音频同步**：与原始歌曲完美同步
- 💻 **IDE模拟**：真实的IntelliJ IDEA界面
- 🎨 **视觉效果**：动态代码输入、错误通知和动画
- 🐱 **彩虹猫进度**：带有动画进度条的Git推送模拟
- ⚠️ **错误轰炸**：执行阶段的多个错误通知
- 🎮 **交互控制**：播放、暂停和停止功能

### 使用方法

1. 在网页浏览器中打开 `index.html`
2. 点击IntelliJ IDEA启动屏幕开始
3. 使用运行按钮启动体验
4. 观看代码编辑器随歌曲输入
5. 体验同步的视觉效果和动画

### 技术细节

- **纯HTML/CSS/JavaScript**：无外部依赖
- **音频文件**：需要同目录下的 `world-execute-me.wav` 文件
- **响应式设计**：支持桌面和移动设备
- **跨浏览器兼容**：在现代浏览器上测试通过

### Docker 部署

#### 快速开始

```bash
# 拉取并运行 Docker 镜像
docker run -d -p 8080:80 yourusername/world-execute-me

# 或使用 docker-compose
docker-compose up -d
```

#### 构建和部署

```bash
# 构建镜像
docker build -t world-execute-me .

# 本地运行
docker run -d -p 8080:80 world-execute-me

# 推送到 Docker Hub (替换 'yourusername' 为您的 Docker Hub 用户名)
docker tag world-execute-me yourusername/world-execute-me
docker push yourusername/world-execute-me
```

#### 使用部署脚本

**Linux/macOS:**
```bash
# 构建并推送到 Docker Hub
./deploy.sh yourusername

# 仅构建 (不推送)
./deploy.sh
```

**Windows:**
```cmd
# 构建并推送到 Docker Hub
deploy.bat yourusername

# 仅构建 (不推送)
deploy.bat
```

---

## License

This project is for educational and entertainment purposes. The song "world.execute(me);" is the property of momocashew and is used with respect to the original artist's work.

---

*Made with ❤️ for the coding community* 