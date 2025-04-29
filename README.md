# 致知虚拟仿真实验平台

[![vue](https://img.shields.io/badge/vue-3.3.4-brightgreen)](https://vuejs.org/)
[![express](https://img.shields.io/badge/express-5.0.1-blue)](https://expressjs.com/)

在线虚拟实验教学平台，提供电路仿真、实验进度跟踪、教学数据分析等功能，支持多角色协同的教学实验管理模式。

## 项目亮点

- 🧪 沉浸式电路仿真实验环境
- 📊 实时实验数据可视化分析
- 👩🏫 多维度教学数据看板
- 🤖 集成AI实验助手
- 📑 自动化实验报告生成

## 技术栈

### 前端核心

- **Vue3** + Vite 构建
- **ECharts** 数据可视化
- **Three.js** 3D实验场景
- **html2pdf** 报告生成

### 后端核心

- **Express** 服务框架
- **MySQL** 数据存储
- **JWT** 鉴权机制
- **RESTful API** 设计

## 功能模块

### 教师端功能

- 🧑🎓 学生实验进度监控
- 📈 实验完成率趋势分析
- 🎯 实验目标达成统计
- 📦 实验任务批量管理

### 学生端功能

- 🔍 实验项目智能检索
- 🛠️ 虚拟电路搭建仿真
- 📌 实验关键步骤记录
- 📤 实验报告一键导出
- 💬 AI智能实验指导

## 快速启动

### 环境要求

- Node.js 18+
- MySQL 8.0+

### 安装步骤

```bash

# 前端依赖安装
cd frontend
npm install

# 后端依赖安装
cd ../backend
npm install

# 启动前端服务（前端目录下）
npm run dev

# 启动后端服务（后端目录下）
node app.js
