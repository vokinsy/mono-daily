# mono-daily
A streamlined PWA for tracking daily habits, focus sessions, and vitals.
# Dayflow (我的日常)

一个兼顾现代极简审美与神经多样性（Neurodiversity）亲和力的渐进式 Web 应用（PWA）。旨在通过低摩擦、即时反馈的交互设计，减少日常任务启动的认知负荷。

![Platform](https://img.shields.io/badge/Platform-PWA%20%7C%20Web-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Style](https://img.shields.io/badge/Design-Minimalist%20%7C%20Linear%20Style-black?style=flat-square)

---

## ✦ 设计理念

传统的日常工具往往具有过长的操作路径和复杂的表单，这容易导致**启动困难（Task Initiation）**与**执行功能障碍（Executive Dysfunction）**人群产生视觉疲劳与心理抗拒。

本应用从**无痛启动**出发进行构筑：
- **零摩擦交互：** 剔除多余跳转。除随手记外，点击任意功能（饮食、运动、日程）即刻唤起表单，一步到位。
- **视觉舒适度：** 规避高对比度的生硬色块，采用毛玻璃材质（Backdrop Blur）与温和的中性色调，有效缓解长时间使用的信息过载感。
- **时间知觉强化：** 提供沉浸式专注倒计时与全局状态常驻，对抗时间盲点。

## ✨ 核心特性

- 📱 **完整 PWA 支持：** 支持离线秒开、独立窗口运行，可直接作为独立 App 安装至 iOS / Android / PC 主屏幕。
- 📊 **三维状态追踪：** 整合随手记、流线型时间轴、轻量化专注时钟以及无压力的数据统计卡片。
- 🔒 **数据本地化与安全：** 所有数据完全留存于浏览器本地存储（LocalStorage），支持一键导出/导入加密 JSON 备份，绝无隐私外泄风险。
- ⚡ **无外部框架依赖：** 基于纯原生 HTML5, CSS 变量与 Vanilla JS 构建，极速轻量。

## 🚀 快速开始

### 线上使用
本项目已全面适配 HTTPS 容器，可一键部署至 Vercel 或 GitHub Pages。

### 本地运行
由于 PWA 及模块化缓存安全策略限制，请使用本地服务器（而非直接双击 HTML 文件）打开：

```bash
# 使用 Python 快速启动本地服务器
python -m http.server 8080
