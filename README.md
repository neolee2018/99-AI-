# AI播客生成器

## 项目介绍
AI播客生成器是一个基于人工智能的音频内容生成工具，能够自动生成播客内容并输出为音频文件。

## 系统要求
- Python 3.8+
- FFmpeg
- Node.js (用于前端开发)

## 安装指南

### 自动安装 (Linux/macOS)
```bash
./deploy.sh
```

### 手动安装
1. 安装系统依赖:

#### CentOS/RHEL:
```bash
sudo yum install -y python3 python3-pip ffmpeg
```

#### Debian/Ubuntu:
```bash
sudo apt-get update
sudo apt-get install -y python3 python3-pip ffmpeg
```

2. 安装Python依赖:
```bash
pip install -r requirements.txt
```

3. 安装前端依赖:
```bash
cd frontend
npm install
```

## 使用方法

### 启动后端服务
```bash
python backend/app.py
```

### 启动前端开发服务器
```bash
cd frontend
npm run dev
```

### 一键启动 (Windows)
双击运行 `start_app.bat`

## 服务地址
- 后端: http://localhost:5000
- 前端: http://localhost:3000

## 贡献指南
欢迎提交Pull Request或Issue报告问题。