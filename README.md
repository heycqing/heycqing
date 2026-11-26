### 喝咖啡会睡着的工程实践者 👾

**高级前端工程师 → AI 原生工程与确定性质量架构实践者**

专注 **前端架构 / 跨端工程化 / AI 智能体研发与自动化验证体系**。擅长把复杂业务与不确定性极高的 AI 研发过程，拆解为可约束、可测量、可追溯的确定性工程闭环。

> 工程不只是把功能跑通，而是把"为什么这么做"以及"如何证明它真的对了"讲清楚。

---

### 核心进化：AI 原生研发与确定性质量工程

从早期的文档驱动初稿（[DocDrive](https://blog.haiqing.uk/docdrive)）出发，结合真实大型项目的持续打磨，已沉淀出一套完整的 **AI 辅助研发护城河**：

- **🧱 约束工程与白盒化代码治理（Harness Engineering）**
  - 通过禁区声明、跨会话漂移检测、文档同步门禁与因果追溯规范（[`cqing-whitebox-code`](https://github.com/heycqing/cqing-whitebox-code) / [`cqing-better-code`](https://github.com/heycqing/cqing-better-code)），将 AI 编码从“盲盒生成”收敛为**受控的白盒交付**。
  - 贯彻 **「AI 产出证据，不产出结论；人类保留终审裁定」** 的工程铁律，用确定性脚本探针替代主观口头汇报。

- **🎯 意图驱动测试与三层正交验证（IDT + ReDeCheck + VLM）**
  - 自研 [`idt-engine`](https://github.com/heycqing/idt-engine)：将自然语言业务意图编译为结构化 IR（`*.ir.json`），再装配成可评审的 Playwright 测试脚本——**CI 阶段零大模型调用，实现低成本、高稳定的确定性回归**。
  - 构建 **「内存逻辑单测 + 真实浏览器盒模型定量测量 + VLM 多模态视觉审阅 + 端到端业务回归」** 的三层防伪验证闭环，彻底解决“虚拟 DOM 单测全绿、真实屏幕错位溢出”的测试遮蔽陷阱。

- **🤖 多智能体研发协作与原子化交付**
  - 实践「需求契约拆解 → 编码实现与探针自检 → 跨端几何/视觉/E2E 测量 → 只读证据终审 → 原子化提交净化」的多角色协作流水线，确保每次代码入库干净、可审、可回溯。

---

### 工程底座与技术栈

- **前端与跨端架构**：TypeScript / Vue / React / 微信小程序架构与深度性能优化（包体积治理、`setData` 精准更新、H5 首屏加载与渲染链路优化）
- **企业级国际化（i18n）**：具备从方案架构、自动化词条/术语治理到跨团队协作闭环的完整落地经验
- **自动化测试与工具链**：Playwright / Midscene 多模态探针 / Node.js / Chrome MV3 扩展 / MCP & Agent Skills 生态

---

### 代表性开源项目与实践

| 项目 | 说明 | 方向 |
| :--- | :--- | :--- |
| [**idt-engine**](https://github.com/heycqing/idt-engine) | Intent-Driven Testing 引擎：将业务意图编译为 IR，再装配成确定性 Playwright Spec | AI 测试编译 / E2E |
| [**cqing-whitebox-code**](https://github.com/heycqing/cqing-whitebox-code) | 面向 AI 辅助编程的白盒化代码工效与因果追溯规范库 | AI 工程治理 |
| [**cqing-better-code**](https://github.com/heycqing/cqing-better-code) | 跨项目约束工程方法论沉淀库（门禁模板、漂移检测、验证闭环） | Harness Engineering |
| [**doc-kb**](https://github.com/heycqing/doc-kb) | 文档型知识库通用建库/核验/复用模板（无向量库、基于文件系统与交叉核验） | 知识工程 / RAG |
| [**ai-translate**](https://github.com/heycqing/ai-translate) | 轻量 Chrome MV3 双语网页翻译扩展（OpenAI 兼容 + IndexedDB 缓存 + 自动降级） | 浏览器扩展 / 产品 |
| [**qa-review-agent**](https://github.com/heycqing/qa-review-agent) | 面向研发交付的自动化质量评审智能体探索 | Agent / QA |

---

### 持续输出与联系

- ✏️ **个人技术博客**：[blog.haiqing.uk/blog/](https://blog.haiqing.uk/blog/)（2017—2026 持续记录前端底层拆解、性能优化、i18n 与 AI 工程实践，累计 110+ 篇）
- 📄 **早期方法论起点**：[DocDrive：文档驱动的 AI 执行框架](https://blog.haiqing.uk/docdrive)
- 📍 **Base**：Guangdong, China
- 📫 **联系我 / 交流合作**：`heycqing@gmail.com`
