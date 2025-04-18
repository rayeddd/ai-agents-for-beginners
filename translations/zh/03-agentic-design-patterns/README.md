# AI 代理设计原则

## 简介

关于构建 AI 代理系统，有许多不同的思考方式。由于在生成式 AI 设计中，模糊性是一种特性而非缺陷，因此工程师有时会难以确定从哪里开始。我们制定了一套以人为中心的用户体验设计原则，旨在帮助开发者构建以客户为中心的代理系统，以满足他们的业务需求。这些设计原则并不是一种规定性的架构，而是为定义和构建代理体验的团队提供的起点。

一般来说，代理系统应该：

- 扩展和增强人类能力（如头脑风暴、解决问题、自动化等）
- 弥补知识空白（例如帮助快速了解某一知识领域、翻译等）
- 促进并支持我们个人偏好的协作方式
- 让我们成为更好的自己（例如，作为生活教练/任务管理者，帮助我们学习情绪调节和正念技巧，建立韧性等）

## 本课内容

- 什么是代理设计原则
- 实施这些设计原则时需要遵循的指导方针
- 使用这些设计原则的一些示例

## 学习目标

完成本课后，您将能够：

1. 解释什么是代理设计原则
2. 解释使用代理设计原则的指导方针
3. 理解如何使用代理设计原则构建一个代理

## 代理设计原则

![代理设计原则](../../../translated_images/agentic-design-principles.9f32a64bb6e2aa5a1bdffb70111aa724058bc248b1a3dd3c6661344015604cff.zh.png?WT.mc_id=academic-105485-koreyst)

### 代理（空间）

这是代理运行的环境。这些原则指导我们如何设计能够在物理和数字世界中互动的代理。

- **连接而非取代** – 帮助人们与其他人、事件和可操作的知识建立联系，从而促进协作和交流。
  - 代理帮助连接事件、知识和人。
  - 代理拉近人与人之间的距离，而不是取代或贬低人类。
- **易于访问但偶尔隐形** – 代理主要在后台运行，只有在相关且适当的时候才会提醒我们。
  - 代理可在任何设备或平台上轻松被授权用户发现和访问。
  - 代理支持多模态输入和输出（如声音、语音、文本等）。
  - 代理可以在前台与后台之间无缝切换；根据用户需求的感知，在主动和被动模式之间切换。
  - 代理可能以隐形形式运行，但其后台处理路径及与其他代理的协作对用户是透明且可控的。

### 代理（时间）

这是代理如何随着时间运作的方式。这些原则指导我们如何设计跨越过去、现在和未来的代理互动。

- **过去**：回顾包含状态和上下文的历史。
  - 代理通过分析丰富的历史数据（不仅仅是事件、人员或状态）提供更相关的结果。
  - 代理从过去的事件中创建连接，并积极反思记忆以应对当前情境。
- **现在**：更多地引导，而非简单通知。
  - 代理体现了一种全面的互动方式。当事件发生时，代理超越静态通知或其他形式化方式。代理可以简化流程或动态生成提示，在合适的时机引导用户注意。
  - 代理根据上下文环境、社会和文化变化以及用户意图提供信息。
  - 代理的互动可以是渐进的，随着时间的推移在复杂性上演变和成长，从而赋能用户。
- **未来**：适应和进化。
  - 代理适应各种设备、平台和模式。
  - 代理适应用户行为、无障碍需求，并可自由定制。
  - 代理通过持续的用户交互来塑造和进化。

### 代理（核心）

这些是代理设计核心中的关键要素。

- **接受不确定性但建立信任**。
  - 某种程度的代理不确定性是可以预期的。不确定性是代理设计的关键元素。
  - 信任和透明是代理设计的基础层。
  - 用户可以控制代理的开/关状态，并且代理的状态始终清晰可见。

## 实施这些原则的指导方针

在使用上述设计原则时，请遵循以下指导方针：

1. **透明性**：告知用户 AI 的参与方式及其工作原理（包括过去的操作），以及如何提供反馈和修改系统。
2. **控制权**：允许用户自定义、指定偏好和个性化，并对系统及其属性进行控制（包括遗忘功能）。
3. **一致性**：在设备和终端之间提供一致的多模态体验。尽量使用熟悉的 UI/UX 元素（例如，语音交互使用麦克风图标），并尽可能降低用户的认知负担（例如，提供简明的回复、视觉辅助和“了解更多”内容）。

## 如何使用这些原则和指导方针设计一个旅游代理

假设您正在设计一个旅游代理，以下是您可以如何应用设计原则和指导方针的思路：

1. **透明性** – 让用户知道这个旅游代理是由 AI 驱动的代理。提供一些基本的使用说明（例如，一条“你好”消息，示例提示）。在产品页面上清楚记录这一点。显示用户过去提出的提示列表。明确说明如何提供反馈（如点赞或点踩、发送反馈按钮等）。清楚说明代理是否存在使用或主题限制。
2. **控制权** – 确保用户可以清楚地了解如何修改已创建的代理，例如通过系统提示。允许用户选择代理的详细程度、写作风格，以及代理不应讨论的主题。让用户查看并删除任何相关文件或数据、提示以及过去的对话。
3. **一致性** – 确保用于分享提示、添加文件或照片、标记某人或某物的图标是标准且易于识别的。使用回形针图标表示文件上传/共享，使用图片图标表示上传图形。

## 其他资源
- [Practices for Governing Agentic AI Systems | OpenAI](https://openai.com)
- [The HAX Toolkit Project - Microsoft Research](https://microsoft.com)
- [Responsible AI Toolbox](https://responsibleaitoolbox.ai)

**免责声明**：  
本文件使用基于机器的人工智能翻译服务进行翻译。尽管我们尽力确保准确性，但请注意，自动翻译可能包含错误或不准确之处。应以原始语言的文件为权威来源。对于关键信息，建议寻求专业人工翻译。对于因使用本翻译而引起的任何误解或误读，我们概不负责。