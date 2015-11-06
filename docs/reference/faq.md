---
type: doc
layout: reference
category: FAQ
title: FAQ
---

# 常见问题

## 常见问题

### Kotlin是什么？

1、一种静态类型语言。

2、可运行于JVM和JavaScript虚拟机。

3、工业用途的通用语言。

4、由JetBrains公司的团队开发和维护。

5、开源语言，并且有外部贡献者。


### 为什么需要一个新语言？

在JetBrains公司，我们已经在Java平台上开发很长时间了，深知Java是多么的好。

另一方面，我们也知道了Java编程语言有某些局限和问题，它们因为向后兼容问题而无法或很难修复。

我们知道Java还会坚持很久，但我们相信社区会受益于一个新的运行于JVM的静态类型语言，从而免于遗留问题和获得开发者们迫切渴求的特性。


该项目蕴含的主要设计思想是：

* 兼容Java
* 编译速度至少和Java一样快
* Make it safer than Java, i.e. statically check for common pitfalls such as null pointer dereference,
* Make it more concise than Java by supporting variable type inference, higher-order functions (closures), extension functions, mixins and first-class delegation, etc;
* And, keeping the useful level of expressiveness (see above), make it way simpler than the most mature competitor – Scala.

### 如何授权？

Kotlin is an OSS language and is licensed under the Apache 2 OSS License. The IntelliJ Plug-in is also OSS.

It is hosted on GitHub and we happily accept contributors


### Is it Java Compatible?

Yes. The compiler emits Java byte-code. Kotlin can call Java, and Java can call Kotlin. See [Java interoperability](java-interop.html).


### Is there tooling support?

Yes. There is an IntelliJ IDEA plugin that is available as an OSS project under the Apache 2 License. You can use Kotlin both
 in the [free OSS Community Edition and Ultimate Edition](http://www.jetbrains.com/idea/features/editions_comparison_matrix.html) of IntelliJ IDEA.

### Is there Eclipse support?

Yes. Please refer to the [tutorial](/docs/tutorials/getting-started-eclipse.html) for installation instructions.

### Is there a standalone compiler?

Yes. You can download the standalone compiler and other builds tools from the [release page on GitHub]({{site.data.releases.latest.url}})

### Is Kotlin a Functional Language?

Kotlin is an Object-Orientated language. However it has support for higher-order functions as well as function literals and top-level functions. In addition, there are
a good number of common functional language constructs in the standard Kotlin library (such as map, flatMap, reduce, etc.). Also, there's no clear definition on what a Functional Language is so we couldn't say Kotlin is one.

### Does Kotlin support generics?

Kotlin supports generics. It also supports declaration-site variance and usage-site variance. Kotlin also does not have wildcard types. Inline functions support reified type parameters.

### Are semicolons required?

No. They are optional.

### Are curly braces required?

Yes.

### Why have type declarations on the right?

We believe it makes the code more readable. Besides, it enables some nice syntactic features, for instance, it is easy to leave type annotations out. Scala has also
proven pretty well this is not a problem.

### Will right-handed type declarations effect tooling?

No. It won't. We can still implement suggestions for variable names, etc.

### Is Kotlin extensible?

We are planning on making it extensible in a few ways: from inline functions to annotations and type loaders.

### Can I embed my DSL into the language?

Yes. Kotlin provides a few features that help: Operator overloading, Custom Control Structures via inline functions, Infix function calls, Extension Functions, Annotations and
language quotations.

### What ECMAScript level does the JavaScript support?

Currently at 5.

### Does the JavaScript back-end support module systems?

Yes. There are plans to provide CommonJS and AMD support.


