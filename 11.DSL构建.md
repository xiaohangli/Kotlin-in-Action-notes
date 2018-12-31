## 11.1 从API到DSL
#### &emsp; 11.1.1 领取特定语言的概念
&emsp;&emsp; 领域特定语言（DSL）  
&emsp;&emsp;  最常见的DSL就是SQL和正则表达式。  
&emsp;&emsp; DSL趋向于声明式。  
&emsp;&emsp;  命令式语言描述了执行操作所需步骤的确切序列，而声明式描述语言描述了想要的结果并将执行细节留给了解释它的引擎。
#### &emsp; 11.1.2 内部DSL
&emsp;&emsp;  内部DSL是用通用编程语言编写的程序的一部分。
#### &emsp; 11.1.3 DSL的结构
&emsp;&emsp;  DSL会出现一个通常在其他API中不存在的特征：结构或者说是文本
#### &emsp; 11.1.4 使用内部DSL构建HTML
## 11.2 构建结构化的API：DSL中带接发者的lambda
#### &emsp; 11.2.1 带接受者的lambda和扩展has类型
#### &emsp; 11.2.2 在HTML构建器中使用带接收者的lambda
#### &emsp; 11.2.3 Kotlin构建器：促成抽象和重用
## 11.3 使用“invoke”约定构建更灵活的代码块嵌套
&emsp;&emsp; invoke约定允许把自定义类型的对象当作函数一样调用。
#### &emsp; 11.3.1 “invoke”约定：像函数一样可以调用的对象
&emsp;&emsp; invoke约定除了用括号替换了get约定中的方括号外，类如果定义了使用operator修饰符的invoke方法，就可以被当作函数一样调用。
#### &emsp; 11.3.2 "Invoke"约定和函数式类型
&emsp;&emsp; lambda，除非是内联的，都是被编译成实现了函数或接口（Function等）的类，而这些接口定义了具有对应数量参数的invoke方法。
#### &emsp; 11.3.3 DSL中的“invoke”约定：在Gradle中声明依赖
## 11.4 实践中的Kotlin DSL
#### &emsp; 11.4.1 把中缀调用链接起来：测试框架中的“should”
#### &emsp; 11.4.2 在基本数据类型上定义扩展：处理日期
#### &emsp; 11.4.3 成员扩展函数：为SQL设计的内部DSL
&emsp;&emsp;  成员扩展依然是成员：它们是属于类的。
#### &emsp; 11.4.4 Anko：动态创建Android UI
