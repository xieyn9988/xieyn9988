# 你好，我是 xieyn9988 👋
在线体验 Demo：http://81.68.194.67
(注：部署于 2核2G 个人测试服务器，首次访问或长时间无访问后，模型加载可能需要等待 10-15 秒，请耐心稍候。点击右上角可切换“业务客服”与“知识维护”视角体验。)

- 🎯 定位：专注 LLM 应用落地与大模型微调的 AI 应用工程师 / RAG 架构师。
- 🌱 目前在搞：RAG 智能客服、SaaS 对账、抖音数据分析。
- 🌱 正在深入：LLM 部署、向量数据库调优、领域微调（LoRA/QLoRA）、vLLM。
- 📫 联系我：42030519@qq.com
- ✅ "开放机会：AI 应用 / 跨境数据 / 全栈开发"
- ✅ "Status: Open to opportunities"
- ✅ "目前在寻找：AI 应用 / 数据工程 / 全栈 / FDE前置工程师方向的机会"

---

### 🛠 技术栈

**🧠 LLM 与 检索**
![LangChain](https://img.shields.io/badge/LangChain-1.x-orange?style=flat-square&logo=langchain&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-API-blue?style=flat-square)
![Milvus](https://img.shields.io/badge/Milvus-v2.4-lightblue?style=flat-square&logo=milvus&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0.5-yellow?style=flat-square)
![BGE](https://img.shields.io/badge/BGE-Embedding-red?style=flat-square)

**⚙️ 微调与部署**
![LLaMA-Factory](https://img.shields.io/badge/LLaMA--Factory-0.8.2-black?style=flat-square)
![LoRA/QLoRA](https://img.shields.io/badge/LoRA/QLoRA-Finetune-purple?style=flat-square)
![vLLM](https://img.shields.io/badge/vLLM-Inference-green?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-Ready-blue?style=flat-square&logo=docker&logoColor=white)

**💻 后端与前端**
![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.115-teal?style=flat-square&logo=fastapi&logoColor=white)
![Vue3](https://img.shields.io/badge/Vue3-3.x-green?style=flat-square&logo=vue.js&logoColor=white)

---

## 🚀 我的项目

| 项目 | 说明 | 技术栈 |
|---|---|---|
| **rag-project**<br>*(电商 RAG 系统)* | **基于 LangChain + Milvus + BGE 的双引擎智能客服系统。**<br>🎯 **架构解耦**：基于 Factory 模式实现 Chroma/Milvus 无缝热切换。<br>🚀 **性能调优**：完成 HNSW 参数消融锁定最优值，Hit@1 达 0.98；Warm-up 将首字延迟降低 76%；<br>🔄 **业务闭环**：实现 SSE 流式输出、Badcase 归因与 LoRA 话术微调。 | `LangChain` `Milvus` `DeepSeek` `FastAPI` `vLLM` |
| [auto-bill-check-saas](https://github.com/xieyn9988/auto-bill-check-saas) | 基于 FastAPI + Vue3 + MySQL + Pandas + Docker 的多数据源电商订单自动对账 SaaS 平台（全栈）。支持上传 CSV / Excel / TXT 表 / pdf 表，下拉选择 MySQL 表 混合对账，自动识别差异并生成财务可用的 Excel 报表。Docker 一键部署 | FastAPI, Vue3, MySQL, Pandas, Docker |
| [douyin-monitor](https://github.com/xieyn9988/douyin-monitor) | 基于 Playwright + Whisper + DeepSeek 的抖音内容智能分析系统。自动采集指定账号视频 → LLM 快速分析 → Agent 智能决策 → ASR 深度转写 → 结构化标签输出，为音乐营销决策提供数据支持。 | Python, Playwright, playwright-stealth, yt-dlp, faster-whisper, DeepSeek |
| [cross-border-ai-data-site](https://github.com/xieyn9988/cross-border-ai-data-site) | 面向跨境电商中小卖家的 AI 数据分析站点。覆盖订单 / 库存 / 营销 / 财务 / 决策 / 客户 六大类业务，16 个分析场景，一次上传 CSV，一键得到业务洞察。字段驱动架构，支持多文件上传、多币种折算、结果可视化、移动端适配。 | Python, FastAPI, Pandas, 原生 JS |

---

## 📊 GitHub 统计

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=xieyn9988&layout=compact&theme=default)

---

## 🎯 关注方向

- **AI 应用落地**：RAG、Agent、LLM 工程化
- **跨境数据自动化**：订单 / 库存 / 广告 / 财务
- **数据工程**：清洗、聚合、可视化
- **DevOps**：Docker、CI/CD、云部署

---

⭐️ 如果我的项目对你有帮助，欢迎 Star
