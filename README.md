# MiLi 静态资源 CDN

MiLi 平台前端构建产物，通过 jsDelivr CDN 分发。

## 内容
- `obp/` - OBP 驾驶舱前端（Vue3 SPA）
- `cpq/` - CPQ 报价系统前端（React SPA）

## 说明
- 本仓库只包含前端构建产物（编译后的 JS/CSS）
- 不包含任何后端代码、数据库、API 密钥
- 业务数据全部在后端，运行时通过 API 动态获取，不经过 jsDelivr
