# 深圳大学成人本科学位英语备考仓库

本仓库用于长期整理和使用“深圳大学成人本科学位英语考试”备考资料，覆盖资料归档、日常练习、AI 辅助学习三条主线，方便个人持续补充、复盘和阶段性自测。

根据当前考纲，重点围绕以下 5 类题型展开整理与训练：

- 词汇和语法
- 完形填空
- 阅读理解
- 汉译英
- 短文写作

## 适用场景

- 统一存放考纲、考试须知、历年试卷和参考资料
- 按天记录学习内容、错题、阶段测验和复盘结果
- 配合 AI 生成模拟题、解析、专项练习和作文反馈

## 目录结构

```text
szu-degree-english-prep/
├── README.md
├── 01-materials/
│   ├── README.md
│   ├── 01-syllabus/
│   ├── 02-papers/
│   │   ├── szu/
│   │   └── other/
│   ├── 03-vocab/
│   ├── 04-grammar/
│   ├── 05-writing/
│   └── 06-notes/
├── 02-practice/
│   ├── README.md
│   ├── 01-daily-log/
│   ├── 02-error-log/
│   ├── 03-mock-tests/
│   ├── 11-vocab-grammar/
│   ├── 12-cloze/
│   ├── 13-reading/
│   ├── 14-translation/
│   ├── 15-writing/
│   └── 90-weekly-review/
├── 03-ai/
│   ├── README.md
│   ├── 01-prompts/
│   ├── 02-generated-questions/
│   ├── 03-generated-analysis/
│   ├── 04-weakness-drills/
│   ├── 11-vocab-grammar/
│   ├── 12-cloze/
│   ├── 13-reading/
│   ├── 14-translation/
│   ├── 15-writing/
│   ├── 05-speaking-writing-feedback/
│   └── 90-mock-papers/
└── 99-templates/
    ├── daily-study-log.md
    ├── error-log.md
    ├── mock-test-log.md
    └── ai-prompts.md
```

## 各目录怎么用

### `01-materials`

用于资料整理和长期归档。

- `01-syllabus`：放考纲、考试须知、报名或考试安排说明
- `02-papers/szu`：放深大学位英语样卷、历年真题、参考答案
- `02-papers/other`：放广东学位英语或其他可参考试卷
- `03-vocab`：放高频词汇、词组、易混词、记忆清单
- `04-grammar`：放语法总结、题型语法点、常错规则
- `05-writing`：放作文模板、万能句型、常见话题素材
- `06-notes`：放章节笔记、题型技巧、阶段总结

### `02-practice`

用于日常练习和复盘。

- `01-daily-log`：每天一份学习记录
- `02-error-log`：错题分类整理与复盘
- `03-mock-tests`：完整模拟测验记录、得分和问题总结
- `11-vocab-grammar`：词汇和语法专项练习
- `12-cloze`：完形填空专项训练
- `13-reading`：阅读理解专项训练
- `14-translation`：汉译英专项训练
- `15-writing`：短文写作专项训练
- `90-weekly-review`：每周复盘、阶段总结、下周计划

### `03-ai`

用于 AI 辅助备考和生成内容管理。

- `01-prompts`：沉淀常用提示词，减少重复提问
- `02-generated-questions`：保存 AI 生成的单项题、阅读题、作文题等
- `03-generated-analysis`：保存 AI 对真题、错题、作文的解析
- `04-weakness-drills`：针对薄弱点生成专项训练
- `11-vocab-grammar`：AI 生成词汇和语法题、语法辨析
- `12-cloze`：AI 生成完形填空题和结构讲解
- `13-reading`：AI 生成阅读文章、设题和定位解析
- `14-translation`：AI 生成句子翻译和表达替换训练
- `15-writing`：AI 生成作文题、范文、批改与提分建议
- `05-speaking-writing-feedback`：保存作文润色、表达替换、评分反馈
- `90-mock-papers`：AI 生成整套模拟卷和阶段测试

## 平时如何使用这个仓库

建议按下面的节奏使用：

1. 新拿到资料时，先放入 `01-materials` 对应目录。
2. 每天学习后，在 `02-practice/01-daily-log` 新建一份当日记录。
3. 做题中出现错题时，及时写入 `02-practice/02-error-log`。
4. 每周至少完成一次模拟练习，并记录到 `02-practice/03-mock-tests`。
5. 遇到薄弱题型时，用 `03-ai/01-prompts` 中的提示词让 AI 生成专项题。
6. 把 AI 生成的题目、解析和复盘结果分别沉淀到 `03-ai` 对应目录，避免内容散落在聊天记录里。

更贴合日常执行时，可以这样分流：

- 日练单项、词汇、语法题，放到 `02-practice/11-vocab-grammar`
- 每周安排 2 到 3 次完形训练，放到 `02-practice/12-cloze`
- 阅读真题和精读材料，放到 `02-practice/13-reading`
- 翻译句子积累与改写，放到 `02-practice/14-translation`
- 作文练习、提纲、修改稿，放到 `02-practice/15-writing`
- 每周末整理一份复盘，放到 `02-practice/90-weekly-review`

## 如何结合 AI 备考

### 1. 生成模拟题

可让 AI 按深大学位英语风格生成：

- 词汇与语法选择题
- 阅读理解题
- 完形填空题
- 翻译题
- 作文题

生成后的题目建议按日期或主题保存到 `03-ai/02-generated-questions`。

### 2. 获取解析

做完题后，把答案和思路交给 AI，请它输出：

- 正确答案
- 每题解析
- 错因判断
- 对应知识点
- 复习建议

解析可保存到 `03-ai/03-generated-analysis`。

### 3. 错题复盘

把错题贴给 AI，让它帮助你：

- 判断是词汇、语法、阅读定位还是理解偏差问题
- 提炼重复出错模式
- 生成 5 到 10 道同类型强化题

这些内容建议存入 `02-practice/02-error-log` 和 `03-ai/04-weakness-drills`。

### 4. 模拟测验

可以让 AI 组一套 30 到 60 分钟的小测或整套模拟卷，并要求：

- 限定题量和题型
- 给出参考答案
- 测后按正确率点评
- 输出下一阶段复习建议

测试记录保存在 `02-practice/03-mock-tests`。

## 使用建议

- 文件名尽量使用 `YYYY-MM-DD-主题.md` 形式，方便排序
- 真题和官方资料尽量保留原文件，不随意覆盖
- 阶段复盘建议每周一份、每月一份
- 常用模板统一从 `99-templates` 复制后再填写
