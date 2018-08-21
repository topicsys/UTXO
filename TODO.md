需要用更高阶的带有逻辑分支的 DSL 代替 Bitcoin 中的脚本代码。

例如：收款脚本变为`{hash(owner.pub)==1GgCAoxxx}`（自动拼接到`提款`代码，执行结果同样为`true/false`），没有空格，没有`return`关键字，整体长度变短。
 - 注意这里的`owner.pub`为特定的变量关键字，具体待定义。
 
