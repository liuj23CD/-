	课程概览
讲师: 陈恺，上海人工智能实验室青年科学家
主题: 书生·浦语大模型全链路开源体系
视频录屏: Bilibili视频链接 
	书生·浦语大模型介绍
发展历史: 介绍了InternLM2的发展历程，从23年6月份发布1.0版本，不断完善不同量级的LLM模型。
全链路开源体系: 包含数据准备（书生·万卷）、预训练（InternLM-Train）、微调（XTuner）、部署（LMDeploy）、评测（OpenCompass）、应用（LagentAgentLego）等环节。 image image
	大模型的发展趋势
专用模型: 针对特定任务设计。
通用大模型: 一个模型应对多种任务、多种模态，如文本、语音、图像等。 image
	InternLM2的主要亮点
超长上下文支持: 能够处理长达200k的上下文。
综合性能提升: 在多个维度和基准评估中表现优异。
对话和创作体验: 提供优秀的对话和创作体验。
工具调用能力: 整体升级，支持上传表格进行数据分析和画图展示。
数理能力和数据分析: 实用的数据功能，支持机器学习建模。
模型到应用的典型流程
模型选型: 根据业务需求选择合适的模型。
业务场景分析: 评估算力和环境交互需求。
参数微调: 根据场景选择微调形式。
	环境交互类型选择: 构建智能体（agent）。
构建智能体: 根据需求构建。
模型评测: 使用OpenCompass等工具进行评测。
模型部署: 将模型部署到实际应用中。 image
	InternLM2技术报告要点
预训练: 包括高质量的32k文本和位置编码外推。
监督微调（SFT）: 提升模型在特定任务上的表现。
强化学习（RLHF）: 基于人类反馈进行优化。
条件在线RLHF（COOL RLHF）: 解决偏好冲突，减少奖励作弊。
模型结构: 在Transformer架构基础上进行改进，提高训练效率和性能。
