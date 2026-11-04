# IANGO 智能获客系统使用指南

## 已为你准备的两份核心文件

1. **IANGO_Company_Navigation_Skill.md**  
   公司导航 Skill。把公司基本信息、产品线、定制能力、认证、目标客户等完整结构化。可直接导入 Claude Code / Cursor / Cline / Hermes 等作为 Skill 使用，让任何智能体都“认识”你们公司。

2. **IANGO_Custom_Lead_Gen_Agent.md**  
   专属获客智能体系统提示词。基于之前推荐的开源项目（smart-trade-ai、B2B Lead Hunter、AI_Find_Customer 等）定制，针对衣架产品（木制、金属、塑料、奢侈品、酒店等）设计了 ICP、搜索策略、背调要点和开发信逻辑。

## 推荐落地方式（从易到难）

### 方案 A：最快上手（推荐先试）
- 使用 **smart-trade-ai**（本地运行）或 **B2B Lead Hunter Skill**
- 把上面两个文件内容作为 Skill / 系统提示加载进去
- 配置搜索 API + LLM Key + 自己的 SMTP
- 直接开始跑线索，人工审核后发送

### 方案 B：完整自建系统
- 基于 **B-agent** 或 **AI_Find_Customer** 部署
- 把公司知识库导入 RAG
- 按 Custom Lead Gen Agent 的流程改造评分和邮件模板

### 方案 C：Grok Bot 常驻智能体
如果你想让我帮你创建一个长期运行的 Grok Bot 来做日常获客，请告诉我，我可以马上为你设置。

## 下一步建议
1. 先阅读并微调两份文件（补充你们实际常用的产品型号、价格区间、主推市场等）
2. 选定一个开源项目开始部署
3. 告诉我你的主推产品系列和重点目标市场（例如：北美时尚品牌、欧洲酒店、中东零售等），我可以进一步细化搜索关键词和邮件模板

需要我现在帮你：
- 生成具体的开发信模板示例？
- 针对某个目标市场写一组搜索关键词？
- 创建一个 Grok Bot 来跑这个流程？

直接告诉我就行。
