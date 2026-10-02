# 公开任务清单

更新：2026-10-03。44 项任务均待开始。这里仅包含公开概述，完整设计及验收记录保留私有。

| 编号 | 阶段 | 任务 | 概述 | 前置任务 | 状态 |
| --- | --- | --- | --- | --- | --- |
| [SF-P0-01](https://github.com/xdgf558/station-cat-season-forge/issues/1) | P0 | 复核产品默认项、文档冲突与成长风险 | 复核产品方向、设计默认项与待解决问题，明确后续工作的基线。 | — | TODO |
| [SF-P0-02](https://github.com/xdgf558/station-cat-season-forge/issues/2) | P0 | 核查真实主站、既有数据与集成边界 | 核查现有网站与独立游戏项目的连接边界和可用环境。 | SF-P0-01 | TODO |
| [SF-P0-03](https://github.com/xdgf558/station-cat-season-forge/issues/3) | P0 | 验证最小 Unity Web 构建与浏览器交付 | 验证网页客户端的基本构建与浏览器运行方式。 | SF-P0-01、SF-P0-02 | TODO |
| [SF-P0-04](https://github.com/xdgf558/station-cat-season-forge/issues/4) | P0 | 验证预发布身份桥与信任边界 | 验证游戏与现有网站入口的基础连接。 | SF-P0-02 | TODO |
| [SF-P0-05](https://github.com/xdgf558/station-cat-season-forge/issues/5) | P0 | 验证最小事务模型与资产一致性 | 验证关键数据操作的一致性与失败恢复方式。 | SF-P0-02 | TODO |
| [SF-P1-01](https://github.com/xdgf558/station-cat-season-forge/issues/6) | P1 | 建立赛季数据迁移与幂等入季 | 建立游戏数据基础与玩家加入流程。 | SF-P0-03、SF-P0-04、SF-P0-05 | TODO |
| [SF-P1-02](https://github.com/xdgf558/station-cat-season-forge/issues/7) | P1 | 实现可信身份、资源授权与缓存隔离 | 完善账号访问边界与不同用户之间的数据隔离。 | SF-P1-01 | TODO |
| [SF-P1-03](https://github.com/xdgf558/station-cat-season-forge/issues/8) | P1 | 实现幂等命令、版本冲突与数值边界 | 完善重复请求、状态冲突与异常输入的处理。 | SF-P1-01、SF-P1-02 | TODO |
| [SF-P1-04](https://github.com/xdgf558/station-cat-season-forge/issues/9) | P1 | 实现库存、所有权和容量预留 | 建立物品库存、归属与容量管理基础。 | SF-P1-03 | TODO |
| [SF-P1-05](https://github.com/xdgf558/station-cat-season-forge/issues/10) | P1 | 实现钱包账本、审计与基础管理开关 | 建立游戏经济记录与基础管理能力。 | SF-P1-03 | TODO |
| [SF-P2-01](https://github.com/xdgf558/station-cat-season-forge/issues/11) | P2 | 实现确定性战斗核心与状态结算 | 建立可复核的自动战斗逻辑与状态处理。 | SF-P1-03 | TODO |
| [SF-P2-02](https://github.com/xdgf558/station-cat-season-forge/issues/12) | P2 | 实现早期配装、技能执行和药水策略 | 实现早期配装、技能与消耗品的基础策略。 | SF-P2-01、SF-P1-04 | TODO |
| [SF-P2-03](https://github.com/xdgf558/station-cat-season-forge/issues/13) | P2 | 实现可信开局、活动锁与战斗快照 | 实现可靠的战斗开始流程与状态保护。 | SF-P2-02、SF-P1-04、SF-P1-05 | TODO |
| [SF-P2-04](https://github.com/xdgf558/station-cat-season-forge/issues/14) | P2 | 实现墙钟结算、重连和资源释放 | 完善战斗结算、断线恢复与资源返还。 | SF-P2-03 | TODO |
| [SF-P2-05](https://github.com/xdgf558/station-cat-season-forge/issues/15) | P2 | 实现等级奖励、首通进度与经验衰减 | 实现角色成长、关卡进度与奖励发放。 | SF-P2-04 | TODO |
| [SF-P2-06](https://github.com/xdgf558/station-cat-season-forge/issues/16) | P2 | 交付早期关卡的 Unity 战斗原型 | 交付可体验的早期关卡与战斗展示闭环。 | SF-P2-05 | TODO |
| [SF-P3-01](https://github.com/xdgf558/station-cat-season-forge/issues/17) | P3 | 落地配方配置、蓝图学习和装备资格 | 建立配方、蓝图学习与装备使用流程。 | SF-P2-06 | TODO |
| [SF-P3-02](https://github.com/xdgf558/station-cat-season-forge/issues/18) | P3 | 实现特色掉落、独立保底与关键蓝图恢复 | 完善特色蓝图获取与关键内容恢复流程。 | SF-P3-01 | TODO |
| [SF-P3-03](https://github.com/xdgf558/station-cat-season-forge/issues/19) | P3 | 实现原子制造、熟练度和随机词条 | 实现可靠的装备制造、制作成长与随机属性。 | SF-P3-01、SF-P1-05 | TODO |
| [SF-P3-04](https://github.com/xdgf558/station-cat-season-forge/issues/20) | P3 | 实现绑定传播与基于快照的分解 | 完善物品绑定、材料返还与分解规则。 | SF-P3-03 | TODO |
| [SF-P3-05](https://github.com/xdgf558/station-cat-season-forge/issues/21) | P3 | 实现耐久维修、教学权益与破产恢复 | 实现装备维护、教学与资源不足时的恢复路径。 | SF-P3-03 | TODO |
| [SF-P3-06](https://github.com/xdgf558/station-cat-season-forge/issues/22) | P3 | 交付制作仓库体验与基础经济闭环 | 完善制作与仓库界面，验证基础成长体验。 | SF-P3-02、SF-P3-04、SF-P3-05 | TODO |
| [SF-P4-01](https://github.com/xdgf558/station-cat-season-forge/issues/23) | P4 | 交付第一批关卡内容 | 交付首批扩展关卡并验证早期机制教学。 | SF-P3-06、SF-P4-06 | TODO |
| [SF-P4-02](https://github.com/xdgf558/station-cat-season-forge/issues/24) | P4 | 交付第二批关卡内容 | 交付下一批关卡并验证装备与角色成长衔接。 | SF-P4-01 | TODO |
| [SF-P4-03](https://github.com/xdgf558/station-cat-season-forge/issues/25) | P4 | 交付第三批关卡内容 | 交付中段关卡并验证机制组合与推进节奏。 | SF-P4-02 | TODO |
| [SF-P4-04](https://github.com/xdgf558/station-cat-season-forge/issues/26) | P4 | 交付第四批关卡内容 | 交付后段关卡并验证策略变化与战斗反馈。 | SF-P4-03 | TODO |
| [SF-P4-05](https://github.com/xdgf558/station-cat-season-forge/issues/27) | P4 | 交付第五批关卡与主线结局 | 交付最终批次关卡与主线完成体验。 | SF-P4-04 | TODO |
| [SF-P4-06](https://github.com/xdgf558/station-cat-season-forge/issues/28) | P4 | 完成成长配置、免费重置和技能面板 | 完善角色与技能配置、调整和成长展示。 | SF-P3-06 | TODO |
| [SF-P4-07](https://github.com/xdgf558/station-cat-season-forge/issues/29) | P4 | 验证完整成长路线与重复游玩目标 | 验证完整成长路线与可选市场之外的主线体验。 | SF-P4-05、SF-P4-06 | TODO |
| [SF-P5-01](https://github.com/xdgf558/station-cat-season-forge/issues/30) | P5 | 实现寄售上架、资格和权威查询 | 实现可选寄售市场的基础上架与浏览流程。 | SF-P3-06、SF-P1-04 | TODO |
| [SF-P5-02](https://github.com/xdgf558/station-cat-season-forge/issues/31) | P5 | 实现原子购买、手续费与交易重试 | 完善交易购买、结算与异常恢复。 | SF-P5-01、SF-P1-05 | TODO |
| [SF-P5-03](https://github.com/xdgf558/station-cat-season-forge/issues/32) | P5 | 实现撤单、到期与停市安全路径 | 完善商品撤回、到期和市场暂停时的处理。 | SF-P5-02 | TODO |
| [SF-P5-04](https://github.com/xdgf558/station-cat-season-forge/issues/33) | P5 | 交付市场体验与独立测试域灰度准备 | 完成市场界面与集成验证，准备分阶段开放。 | SF-P5-03、SF-P4-07 | TODO |
| [SF-P6-01](https://github.com/xdgf558/station-cat-season-forge/issues/34) | P6 | 实现可信最好成绩与榜单版本 | 实现可信成绩记录与排行榜展示。 | SF-P4-07、SF-P1-05 | TODO |
| [SF-P6-02](https://github.com/xdgf558/station-cat-season-forge/issues/35) | P6 | 实现赛季截止与迟到战斗结算 | 完善赛季结束时的业务边界与结算处理。 | SF-P5-03、SF-P2-04 | TODO |
| [SF-P6-03](https://github.com/xdgf558/station-cat-season-forge/issues/36) | P6 | 实现新季隔离并演练赛季切换 | 实现新赛季初始化并演练历史与当前进度隔离。 | SF-P6-02、SF-P6-01 | TODO |
| [SF-P6-04](https://github.com/xdgf558/station-cat-season-forge/issues/37) | P6 | 实现历史归档与幂等纯外观奖励 | 实现历史展示、归档与纪念奖励流程。 | SF-P6-03、SF-P1-05 | TODO |
| [SF-P7-01](https://github.com/xdgf558/station-cat-season-forge/issues/38) | P7 | 验证 Web 交付、分章资源与移动端恢复 | 验证网页交付、资源加载与移动设备恢复体验。 | SF-P4-07、SF-P5-04、SF-P6-04 | TODO |
| [SF-P7-02](https://github.com/xdgf558/station-cat-season-forge/issues/39) | P7 | 验证混合负载、日志与降级阈值 | 评估运行负载与容量，验证异常时的保护措施。 | SF-P5-04、SF-P6-04 | TODO |
| [SF-P7-03](https://github.com/xdgf558/station-cat-season-forge/issues/40) | P7 | 完成身份、资产与管理攻击面回归 | 复核账号、资产与管理功能的安全边界。 | SF-P5-04、SF-P6-04 | TODO |
| [SF-P7-04](https://github.com/xdgf558/station-cat-season-forge/issues/41) | P7 | 完成一致性备份与隔离恢复演练 | 演练数据备份与隔离恢复，核查记录一致性。 | SF-P6-04 | TODO |
| [SF-P7-05](https://github.com/xdgf558/station-cat-season-forge/issues/42) | P7 | 形成发布候选并完成主站与合同回归 | 汇总发布候选证据并验证现有网站与兼容性。 | SF-P7-01、SF-P7-02、SF-P7-03、SF-P7-04 | TODO |
| [SF-P8-01](https://github.com/xdgf558/station-cat-season-forge/issues/43) | P8 | 经明确授权发布并执行小范围灰度 | 在获得明确授权后执行发布和小范围验证。 | SF-P7-05 | TODO |
| [SF-P8-02](https://github.com/xdgf558/station-cat-season-forge/issues/44) | P8 | 观察经济与运行指标并按门槛扩大开放 | 观察上线表现并依据验证结果调整开放范围。 | SF-P8-01 | TODO |
