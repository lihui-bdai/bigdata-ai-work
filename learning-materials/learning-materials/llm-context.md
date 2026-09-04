```
# 大模型的上下文（Context）

## 概念解释
上下文是指大模型在生成回答时能够"看到"和参考的历史信息。

## 核心机制
- 输入序列：模型接收的所有文本
- 注意力机制：模型关注上下文中的关键部分
- 窗口限制：模型一次能处理的最大长度

## 应用场景
长文档总结、多轮对话、代码生成

## 使用边界
超出上下文窗口的信息会被遗忘，模型不能无限记住所有内容。

## 我的理解
上下文就像是模型的"短期记忆"。你给它多少信息，它就只能基于这些信息回答。所以我们在问问题的时候，提供清晰的上下文比问题本身更重要。

## 参考来源
- Wikipedia: Large language model - Context window
  https://en.wikipedia.org/wiki/Large_language_model#Context_window
- 李沐：大模型上下文理解能力详解
  https://zhuanlan.zhihu.com/p/xxxxxxxx
