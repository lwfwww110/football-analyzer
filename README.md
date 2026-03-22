[README.md](https://github.com/user-attachments/files/26164024/README.md)
# 足球量化分析系统

## 功能特点

- 主客场分离编码法
- 分段因数分析
- 复合实力系数计算
- 分时实力线可视化
- 赔率对比与背离检测
- 多维度碰撞分析
- ML机器学习训练模块
- ROI回测分析

## 部署说明

### Railway部署步骤

1. 访问 [Railway.app](https://railway.app)
2. 使用GitHub账号登录
3. 点击 "New Project" → "Deploy from GitHub repo"
4. 选择此仓库
5. 添加环境变量 `FOOTBALL_API_KEY`
6. 部署完成后获得公网地址

### 环境变量

- `FOOTBALL_API_KEY`: football-data.org API密钥
- `PORT`: 服务器端口（自动设置）

## 本地运行

```bash
python server.py
```

访问 http://localhost:8080/football-analyzer-v3.html

## 技术栈

- 前端: HTML5 + CSS3 + JavaScript
- 后端: Python 3.9
- API: football-data.org
