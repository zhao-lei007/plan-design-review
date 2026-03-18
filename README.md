# plan-design-review

一个用于**设计计划审查（design plan review，计划级设计补全）**的 Skill。

## 这个 Skill 是干什么的
它不看“已经上线的页面”，而是看**还没做出来的计划**有没有把设计讲清楚。

它会检查：
- information architecture（信息架构）
- interaction states（交互状态）
- user journey（用户旅程）
- AI slop risk（AI 套壳感风险）
- design system alignment（是否和设计系统一致）
- responsive / accessibility（响应式与可访问性）

目标是：在实现前把设计缺口补上，避免工程师靠猜。

## 什么时候用
适合这些场景：
- PRD／方案文档里有 UI，但描述还不够具体
- 你想在开工前先把设计债堵住
- 你不想让“上线后再 polish”变成永久借口

## 核心输出
通常会产出：
- 每个设计维度的评分
- 缺失设计决策的补完建议
- 计划中的状态表、层级说明、用户旅程说明
- 哪些设计决策仍需显式拍板

## 不适合的场景
它不适合：
- 纯后端计划
- 已有真实页面、要做视觉审计
- 只想做 CEO／业务层面的 scope 判断

## 相关 Skills
- `design-consultation`：更偏设计方向咨询
- `design-review`：更偏成品审查
- `plan-eng-review`：更偏工程执行计划

