# Pyramid

Pyramid 是一个基于 **Python 爬虫 + Web 服务** 的数据源框架，  
基于 [PyramidStore](https://github.com/UndCover/PyramidStore) 二次整理与适配，  
主要用于 **影视类 App 及其衍生应用**，通过 Python 爬虫方式提供统一的数据接口。

- 使用 Python 编写爬虫逻辑
- 通过 Pyramid Web 框架对外提供 API
- 作为影视 App 的数据源后端使用

📌 本仓库为 **PyramidStore 的集成与使用示例项目**，方便快速部署与二次开发。

---

## 📦 项目来源

- **PyramidStore（基础框架）**  
  https://github.com/UndCover/PyramidStore

- **原版 Pyramid 源码**  
  https://github.com/UndCover/Pyramid

- **影视版 Pyramid（App 端集成示例）**  
  https://github.com/FongMi/TV/tree/fongmi/chaquo

---

## ✨ 项目特点

- 使用 **Python 编写爬虫**，逻辑清晰、可维护性强
- 支持多站点、多接口扩展
- 与影视 App 解耦，仅作为数据源服务
- 适合自建、学习、研究使用
- 可运行于本地或服务器环境

---

## 🗂 项目用途说明

本项目主要用于：

- 影视类 App 的数据接口服务
- Python 爬虫学习与实践
- Pyramid 框架的实际使用示例
- 自定义数据源 / 聚合接口

---

## 🚀 基本使用说明

### 1️⃣ 环境与依赖

- Python 3.8+
- 已开启 **存储权限**（非常重要）
```bash
pip install -r requirements.txt
```
> ⚠️ **一定要开启存储权限！一定要开启存储权限！一定要开启存储权限！**

---

### 2️⃣ 写法

[Python爬虫写法参考spider.md](https://github.com/lm317379829/PyramidStore/blob/main/spider.md)

