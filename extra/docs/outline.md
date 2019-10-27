# 大纲

## 语法分析 Syntax Analyzer

### 形式语言 Formal Language

> 1. 前提是必须是一种形式语言，有一种特定的分析规则，不会产生歧义
> 2. 计算机使用的语言必须是一种形式语言，才能被语法分析。
> 3. 如 1+2=3 就是一种形式语言，雪落师门（人使用的语言都不是）就不是，因为雪落是名词+动词，但是此时只表示名词（命名实体识别）。
> 4. 因此形式语言对编译器很重要，所有能被编译的语言都是形式语言

给定某一个形式语言的字符串，一定存在一个 函数 F ，使得 F(str) => Syntax tree, 且这个 tree 不会产生歧义

> F(tokens) => Syntax tree,


### 语法（上下文无关）

形式语言被分析，是根据一种特定的规则，这个规则就成为语法，语法是与上下文无关的。


## 笔记
1. 文法就是语法
2. -> 符号是推出的意思
3. Expr 是表达式的意思 Expression
4. 前缀中缀后缀表达式
5. 符号表 : 词法分析器要分解出关键字、标识符、常量、操作符、界符这五类元素，那么当词法分析器解析出一个token后就要检查这个token是什么类型，基本的实现方法就是查表，查符号表。
6. 词法分析的作用就是两个字——"断词"。



