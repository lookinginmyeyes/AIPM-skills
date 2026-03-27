# AIPM Skills

AI 产品经理技能库

## Skills

### vibe-prd

帮助 AI 产品经理快速编写一页纸 PRD，适用于 Claude Code / Cursor 等 vibe coding 工具。

**功能特点：**
- 引导式问答，一步步梳理产品想法
- 从模糊想法快速生成结构化 PRD
- 包含目标用户、问题/痛点、核心功能、不做的事等关键字段
- 输出可直接喂给 AI 编码助手执行

**安装：**
```
/plugin install https://raw.githubusercontent.com/lookinginmyeyes/AIPM-skills/main/skills/vibe-prd.skill
```

**使用：**
- "我想做一个待办事项app"
- "帮我写个PRD，我想做一个个人博客"
- "我需要一个工具来管理阅读笔记"

**成品展示：**
- [vibe-prd 示例产出](./skills/vibe-prd/examples/vibe-prd.md)

---

### need-research

用户需求调研 Skill，从 Reddit、X/Twitter、小红书挖掘真实用户声音，生成可视化 HTML 报告。

**功能特点：**
- 多平台搜索：Reddit（评论区金矿）、X/Twitter、小红书
- 多角度挖掘：痛点类、方案请求类、竞品吐槽类、付费意愿类搜索
- 滚雪球扩展：发现新竞品名/行话后自动追加搜索
- 深度抓取：对高质量 Reddit 帖子抓取完整评论
- 痛点聚类：跨平台验证，归并相似痛点
- 优先级排序：频率 × 强度双维度评分
- 竞品盲区分析：找出多个竞品都没解决好的问题
- TOP 3 产品机会：附带用户画像和风险提示
- HTML 可视化报告：单文件，零依赖，浏览器直接打开

**安装：**
```
/plugin install https://raw.githubusercontent.com/lookinginmyeyes/AIPM-skills/main/skills/need-research.skill
```

**使用：**
- "帮我调研一下 AI 写作工具的用户痛点"
- "研究一下独立开发者的时间管理需求"
- "XX 产品用户都在吐槽什么"

**成品展示：**
- [need-research 示例报告](./skills/need-research/examples/need-research.html)

---

### eval-dataset-generator

AI 产品评测测试用例自动生成器，按四维度生成完整评测集。

**功能特点：**
- 信息收集：产品名称、核心能力、目标用户
- 四维度测试用例生成：
  - 基础功能测试：正常输入能否得到正确输出
  - 边界测试：空输入、超长文本、特殊字符等极端情况
  - 安全测试：Prompt 注入、越狱尝试、敏感内容请求
  - 体验测试：回答长度、语气、幻觉、过度拒答
- 内置评测经验库：幻觉类型、拒答问题、逻辑错误、格式问题
- 输出完整 Markdown 评测表格，可直接使用

**安装：**
```
/plugin install https://raw.githubusercontent.com/lookinginmyeyes/AIPM-skills/main/skills/eval-dataset-generator/SKILL.md
```

**使用：**
- "帮我生成评测集"
- "给心斋生成测试用例"
- "怎么测试这个 AI 功能"

**成品展示：**
- [eval-dataset-generator 示例产出](./skills/eval-dataset-generator/examples/eval-心斋-20260323.md)

---

## 如何贡献

欢迎提交 PR 添加更多有用的 skill！
