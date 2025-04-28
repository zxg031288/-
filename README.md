# 测量数据趋势管理系统

这是一个用于管理和分析测量数据趋势的 Web 系统。

## 技术栈

- 前端：React + TypeScript + Ant Design
- 后端：FastAPI (Python)
- 数据库：PostgreSQL
- 容器化：Docker + Docker Compose

## 项目结构

```
.
├── frontend/               # 前端 React 应用
├── backend/               # 后端 FastAPI 应用
├── docker/               # Docker 相关配置
├── docker-compose.yml    # Docker Compose 配置文件
└── README.md            # 项目说明文档
```

## 快速开始

1. 确保已安装 Docker 和 Docker Compose

2. 克隆项目并进入项目目录

3. 启动服务
```bash
docker-compose up -d
```

4. 访问系统
- 前端界面：http://localhost:3000
- API 文档：http://localhost:8000/docs

## 功能特性

- 数据采集和存储
- 数据趋势可视化
- 数据分析和报表
- 告警配置和通知
- 用户权限管理 