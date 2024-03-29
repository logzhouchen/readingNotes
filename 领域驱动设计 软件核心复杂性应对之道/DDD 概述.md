DDD(Domain-Driven Design 领域驱动设计)
不一定是面向对象的，但需一种富有表达力的结构来反应领域模型，无论是对象，规则还是工作流 建模范式。

除了领域对象建模，当领域中某部分明显适合于其他建模范式，例如规则引擎 或者 工作流引擎。例如支付收银台规则引擎，通过groovy配置来进行决策逻辑链路，
混合使用不同风格的建模范式使得开发人员能够用最适当的建模方式对特殊概念进行建模。
但将非对象元素 混合 到以面向对象为主的领域模型中去时，需要做到：
1. 不要和建模范式进行对抗： 我们总是可以找到别的方式来考虑领域，找到适合于范式的模型概念；
2. 把通用语言作为依靠的基础；
3. 不要一味依赖UML图：有时使用其他范式风格的图形 或者 简单的语言描述比对象UML图表达得更好；
4. 保持怀疑态度

