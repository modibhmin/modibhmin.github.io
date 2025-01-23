2022 年 11 月，OpenAI 推出了人工智能聊天模型 ChatGPT，再次引发了广泛关注，并掀起了关于 AI 技术对社会影响的热烈讨论。

ChatGPT 是一种专注于对话生成的语言模型，能够根据用户的文本输入生成智能回答。无论是简短的回复还是长篇论述，它都能胜任。GPT 是 Generative Pre-trained Transformer（生成型预训练变换模型）的缩写。以下是学习 ChatGPT 必读的 10 篇核心论文。

---

## 1. Transformer

ChatGPT 使用的 GPT 模型是基于 Transformer 的解码器部分进行改造的。

- **论文标题**: Attention Is All You Need  
- **论文链接**: [https://arxiv.org/pdf/1706.03762.pdf](https://arxiv.org/pdf/1706.03762.pdf)  
- **摘要**: 提出了 Transformer，这是一种完全基于注意力机制的网络结构，摒弃了递归和卷积。实验表明，Transformer 在机器翻译任务中表现优异，训练效率更高，质量更好。

---

## 2. GPT-3

GPT 家族模型基于 Transformer 技术，从 GPT-1 的 12 层发展到 GPT-3 的 96 层。

- **论文标题**: Language Models are Few-Shot Learners  
- **论文链接**: [https://arxiv.org/pdf/2005.14165.pdf](https://arxiv.org/pdf/2005.14165.pdf)  
- **摘要**: GPT-3 是一个拥有 1750 亿参数的自回归语言模型，展示了在少样本学习任务中的强大性能。它无需微调，仅通过文本交互即可完成任务。

---

## 3. InstructGPT

ChatGPT 的训练流程主要参考了 InstructGPT，并在其基础上进行了改进。

- **论文标题**: Training language models to follow instructions with human feedback  
- **论文链接**: [https://arxiv.org/pdf/2203.02155.pdf](https://arxiv.org/pdf/2203.02155.pdf)  
- **摘要**: 通过人类反馈微调 GPT-3，使其更符合用户意图。InstructGPT 在输出质量、真实性和减少有害内容生成方面表现优异。

---

## 4. Sparrow

DeepMind 的 Sparrow 与 InstructGPT 的技术框架类似，但在奖励模型设计上有所创新。

- **论文标题**: Improving alignment of dialogue agents via targeted human judgements  
- **论文链接**: [https://arxiv.org/pdf/2209.14375.pdf](https://arxiv.org/pdf/2209.14375.pdf)  
- **摘要**: Sparrow 通过人类反馈强化学习训练对话代理，使其更有帮助、更准确且更无害。

---

## 5. RLHF

RLHF（Reinforcement Learning from Human Feedback）是 ChatGPT 的核心训练方法之一。

- **论文标题**: Augmenting Reinforcement Learning with Human Feedback  
- **论文链接**: [https://www.cs.utexas.edu/~ai-lab/pubs/ICML_IL11-knox.pdf](https://www.cs.utexas.edu/~ai-lab/pubs/ICML_IL11-knox.pdf)  
- **摘要**: RLHF 通过人类反馈增强强化学习模型的训练效果，显著提高了模型的输出质量。

---

## 6. TAMER

TAMER 框架通过人类反馈指导代理学习，快速实现训练目标。

- **论文标题**: Interactively Shaping Agents via Human Reinforcement  
- **论文链接**: [https://www.cs.utexas.edu/~bradknox/papers/kcap09-knox.pdf](https://www.cs.utexas.edu/~bradknox/papers/kcap09-knox.pdf)  
- **摘要**: TAMER 允许人类通过强化信号互动地塑造代理的行为，显著降低了学习任务的样本复杂性。

---

## 7. PPO

PPO（Proximal Policy Optimization）是 ChatGPT 训练的第三阶段强化学习算法。

- **论文标题**: Proximal Policy Optimization Algorithms  
- **论文链接**: [https://arxiv.org/pdf/1707.06347.pdf](https://arxiv.org/pdf/1707.06347.pdf)  
- **摘要**: PPO 提供了一种高效的策略优化方法，兼具简单性和样本效率，在多种任务中表现优异。

---

## 8. In-Context Learning

ChatGPT 展现了强大的临场学习能力（In-Context Learning），学术界对此仍在探索。

### 8.1 Why Can GPT Learn In-Context?

- **论文标题**: Why Can GPT Learn In-Context? Language Models Secretly Perform Gradient Descent as Meta-Optimizers  
- **论文链接**: [https://arxiv.org/pdf/2212.10559.pdf](https://arxiv.org/pdf/2212.10559.pdf)  

### 8.2 What Learning Algorithm is In-Context Learning?

- **论文标题**: What learning algorithm is in-context learning? Investigations with linear models  
- **论文链接**: [https://arxiv.org/pdf/2211.15661.pdf](https://arxiv.org/pdf/2211.15661.pdf)  

---

## 9. Prompt

Prompt 是 ChatGPT 训练时使用的一种输入模板，能够帮助模型更好地完成下游任务。

- **论文标题**: Pre-train, Prompt, and Predict: A Systematic Survey of Prompting Methods in Natural Language Processing  
- **论文链接**: [https://dl.acm.org/doi/pdf/10.1145/3560815](https://dl.acm.org/doi/pdf/10.1145/3560815)  
- **摘要**: 本文系统性地总结了 Prompt 方法在自然语言处理中的应用，展示了其在少样本学习和零样本学习中的强大能力。

---

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)