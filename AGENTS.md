# CODEBUDDY.md

This file provides guidance to CodeBuddy Code when working with code in this repository.

## 项目概述

本仓库是**量潮数字资产档案**，记录各类数字资产分类定义及平台账号资源管理。作为量潮工作档案的子模块，采用 Git 子模块架构。

## 目录结构

```
.
├── index.md           # 内容摘要入口
├── README.md          # 项目说明
├── CHANGELOG.md       # 版本变更记录
├── category/          # 资产分类
│   ├── profile/       # 工作档案（创始人、沟通、议事、标准化等）
│   └── handbook/      # 手册
├── entity/            # 实体档案
│   └── founder/       # 创始人档案（记忆模型）
└── platform/          # 平台资产（GitHub 等）
```

## 核心概念

### 记忆模型（entity/founder/）

以记忆系统为隐喻构建知识资产体系：

- **工作记忆**：profile（陈述性）+ handbook（程序性）
- **长期记忆**：工作札记（陈述性）+ 工作报告（程序性）

### 信息流转规则

```
创始人档案 → 公司档案：转移职责
主体档案 → 领域档案：积累可复用组件
```

### 访问范围

| 位置 | 访问范围 |
|------|----------|
| GitHub | 公开 |
| 飞书知识库 | 内部 |

## 提交规范

使用 Conventional Commits 格式：

```
feat: 新增功能/内容
docs: 文档更新
refactor: 结构调整
fix: 修复问题
```

## 版本规范

遵循语义化版本（SemVer）：
- 修订号：错别字修正、格式调整
- 次版本：新增内容、新增板块
- 主版本：架构调整

## 发布流程

1. 更新 CHANGELOG.md
2. 提交所有变更
3. 推送到远程

## 相关文档

- 元数据信息位于主仓库 `meta/asset/`
- 父仓库工作指南见 `/Users/mac/repos/quanttide/asset/profile/AGENTS.md`
