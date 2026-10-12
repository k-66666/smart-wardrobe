# 智慧衣柜系统（Smart Wardrobe · Wardrobe Guardian）

软硬结合的智慧衣柜应用：对衣柜内环境（温湿度等）进行监测与数据可视化，并提供衣物分类管理，帮助用户掌握衣物状态、做好防潮防霉。

## 功能

- **环境监测**：衣柜温湿度等环境数据的实时展示
- **数据可视化**：历史数据趋势图表（Recharts），直观掌握环境变化
- **衣物管理**：衣物的分类、录入与状态管理
- **智能提醒**：结合环境数据给出防潮、除湿等养护提示

## 技术栈

- React + TypeScript + Vite
- Tailwind CSS 样式
- Recharts 数据可视化
- Lucide React 图标
- 集成 Google Gemini AI 能力

## 快速开始

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本（TypeScript 编译 + Vite 构建）
npm run build

# 预览构建结果
npm run preview
```

## 项目结构

```
├── App.tsx        # 应用主界面
├── components/    # 监测面板、衣物列表、图表等组件
├── services/      # 数据与 AI 服务封装
├── types.ts       # 类型定义
└── index.tsx      # 入口
```

## 相关项目

- [Smart-APP](https://github.com/k-66666/Smart-APP)：智能防霉柜监控系统（STM32 硬件端 + Android 应用端），同为物联网方向的完整落地项目。

---

作者：Barry（[@k-66666](https://github.com/k-66666)）｜承接 Web 应用与物联网数据端定制开发，欢迎邮件联系：llk6666666@gmail.com
