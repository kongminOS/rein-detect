# 异常/老化检测 · Sentinel

> AI Agent 状态感知与降级预警：不是等它出大事才发现

## 一、要解决的问题
Agent 越用越慢、越用越乱（记忆膨胀、上下文污染、权限混乱）往往渐进发生，没人注意。

## 二、设计思路
监控关键指标（上下文占用率、记忆污染度、成功率）；设降级阈值；到线预警提前干预。

## 三、方法要点
指标监控 + 阈值预警 + 提前干预，避免猝死式故障。

## 四、可落地检查清单
- [ ] 明确它管什么、不管什么
- [ ] 有基线/快照可比对
- [ ] 异常可告警、可干预、可恢复

## 五、关联
完整生态见 [kongminOS](https://github.com/kongminOS)；实证见 [rein-evidence](https://github.com/kongminOS/rein-evidence)。

---
*Kongmin Rein —— 基于三库深度掌握的 AI 治理层。Status: 建构中。License: MIT。*
