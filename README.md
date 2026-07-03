<div align="center">

# DiVo Agent Platform — 企业级 AI Agent 自主治理平台

**数据私有化 · 定制工作流 · 工具技能全部自主掌控 · 让 Agent 带上镣铐跳舞**

[English](README.en.md) · 中文

[![License](https://img.shields.io/badge/License-AGPL%203.0-blue.svg)](LICENSE)](LICENSE)

</div>

---

## 你是谁的问题

企业想用 AI Agent，但面临三对矛盾：

| 矛盾 | 现状 |
|---|---|
| **能力 vs. 合规** | Agent 越聪明越需要自主访问；企业越需要合规越需要锁死边界 |
| **个性化 vs. 一致** | 各部门想定制体验，但 IT 必须统一纳管 |
| **快速上线 vs. 自主可控** | SaaS 产品上手快但数据出域；自己开发又没团队、没工期 |

**DiVo Agent Platform** 的答案：**环境即治理单元**。

---

## 为什么是 DiVo

### 自主治理
DiVo Agent Platform 让你完全掌控 Agent 的运行环境 —— 数据私有化托管，工作流按需定制，工具与技能白名单治理。

### 国产模型全面适配
平台在 LLM 管理层深度适配国内主流国有模型厂商（百度文心一言、阿里通义千问、腾讯混元、华为盘古、智谱 GLM 系列、DeepSeek 系列等），支持企业混部自有模型与国有模型的统一纳管。

### 企业身份对接
支持与公司现有账号体系（OIDC / SAML / CAS 等）对接，组与角色继承沿用企业现有架构。

### 开放可控的 Skill 与 MCP 架构
平台上架的 Skill 与 MCP Server 经过 IT 审核，走企业私有市场，不允许工作空间私建出站通道。

---

## 五大典型客户场景

| 客户类型 | 典型痛点 | DiVo 提供的价值 |
|---|---|---|
| 垂直 IT 服务企业 | 多交付团队，既想用又怕代码出境 | 数据不出境，Agent 环境隔离 |
| 国企 / 大型集团 | 全集团要铺，信息部要能控能查 | 统一纳管，法人实体隔离 |
| 政府 / 事业单位 | 国产化、物理隔离、等保合规 | 完全物理断网部署，日志对等保 |
| 科研 / 高校 | 实验室大量跑 Agent，IT 要代建基座 | IT 统一管基座，科研专注 Prompt |
| 中小微企业 & 独立开发者 | 想让 Agent 跑在自己服务器上，不希望失控 | 一体机镜像，零运维起步 |

---

## 版本对比

| 能力 | 社区版 | 企业版 |
|---|---|---|
| Agent 环境隔离 | ✅ | ✅ |
| 策略治理 | ✅ | ✅ |
| 多模型路由 | ✅ | ✅ |
| Skills 仓库 | 公开源 | 私有市场 |
| OIDC / SSO | ✗ | ✅ |
| 审计日志 | 本地查看 | 集中审计 + 合规报表 |
| 高可用 | 单节点 | 多节点 |

---

## 体验与评估

评估镜像与 POV 环境请咨询 `contact@wangjueju.cn` 获取。

---

## 关于 DiVo

DiVo 是一家专注于 **AI 基础设施与 Governance** 的产品公司。我们认为 AI Agent 要进企业，必须先解决 *在哪里跑、谁能看、跑完留下什么* 这三个问题。DiVo Agent Platform 是答案。

© 2024-2026 DiVo Gen²AI — 王掬琅（Peter Wang）· 王潇奕（Shawn Wang）
项目主站 [wangjueju.cn](https://wangjueju.cn) · 联系邮箱 [contact@wangjueju.cn](mailto:contact@wangjueju.cn)

> **灵感来源**：本平台的设计灵感，源于 George 老师与 DiVo Gen²AI 的 AI 攻城狮们，在长期的各种 HCI、IDE、CLI、Code 一线开发实践中，对"Agent 自由 vs. 治理边界"反复碰撞后的经验总结。

<div align="center">

**[License](LICENSE)** · **contact@wangjueju.cn**

</div>
