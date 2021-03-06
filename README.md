# MySources
Links those are informative for me !

### 1. Equatable, GetHashCode, Implementing Equality
   - [What is the difference between IEqualitycomparer T and IEquatable T](https://stackoverflow.com/questions/9316918/what-is-the-difference-between-iequalitycomparert-and-iequatablet)
   - [How does HashSet compare elements for Equality](https://stackoverflow.com/questions/8952003/how-does-hashset-compare-elements-for-equality)
   - [IEquatablet with GetHashCode](https://stackoverflow.com/questions/58379115/iequatablet-with-gethashcode)
   - [Force child class to override function of ancestor via parent](https://stackoverflow.com/questions/19791178/force-child-class-to-override-function-of-ancestor-via-parent)
   - [Notes to implementers to implement Equals](https://docs.microsoft.com/en-us/dotnet/api/system.iequatable-1?view=netframework-4.8#notes-to-implementers)
   - [Can I enforce the overriding of GetHashCode() and Equals() methods for users of a generic container class?](https://softwareengineering.stackexchange.com/questions/307999/can-i-enforce-the-overriding-of-gethashcode-and-equals-methods-for-users-of)
   - [Should GetHashCode be implemented for IEquatable<T> on mutable types?](https://stackoverflow.com/questions/49055673/should-gethashcode-be-implemented-for-iequatablet-on-mutable-types)


### 2. Interface and Abstract Class
   - [When should I choose inheritance over an interface when designing C# class libraries?](https://stackoverflow.com/questions/5816563/when-should-i-choose-inheritance-over-an-interface-when-designing-c-sharp-class)
   - [What's the difference between implementing an Interface explicitly or implicitly?](https://softwareengineering.stackexchange.com/questions/136319/whats-the-difference-between-implementing-an-interface-explicitly-or-implicitly)
   - [Implicit vs Explicit Interface Implementation](https://stackoverflow.com/questions/598714/implicit-vs-explicit-interface-implementation)
   - [Explicitly marking derived class as implementing interface of base class](https://stackoverflow.com/questions/46541462/explicitly-marking-derived-class-as-implementing-interface-of-base-class)
   - [Overriding fields or properties in subclasses](https://stackoverflow.com/questions/326223/overriding-fields-or-properties-in-subclasses)
   - [Interface vs Abstract Class (general OO)](https://stackoverflow.com/questions/761194/interface-vs-abstract-class-general-oo)
   - [C# Interface Implementation relationship is just “Can-Do” Relationship?](https://stackoverflow.com/questions/255644/c-sharp-interface-implementation-relationship-is-just-can-do-relationship)

### 3. Covariant Return Type Error
   - Docs
     - [CA1061: Do not hide base class methods](https://docs.microsoft.com/en-us/visualstudio/code-quality/ca1061?view=vs-2019)
     - [Framework Design Guidelines](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/)
     - [Covariance and Contravariance in Generics](https://docs.microsoft.com/en-us/dotnet/standard/generics/covariance-and-contravariance)
     - [C# Futures: Covariant Return Types](https://www.infoq.com/news/2020/01/CSharp-Covariant-Return-Types/)

   - Github Issues
     - [Proposal: support covariant return types #357](https://github.com/dotnet/roslyn/issues/357)
     - [Champion "Covariant Return Types" #49](https://github.com/dotnet/csharplang/issues/49)
     - [9.0 candidate](https://github.com/dotnet/csharplang/milestone/15)
     
   - [Hesam Kashefi video](https://www.youtube.com/watch?v=LsKIhuRJbtk&feature=youtu.be)
      
   - Stackoverflow Questions
     - [Why was IEquatable T not made contravariant in T for C# 4.0?](https://stackoverflow.com/questions/3289440/why-was-iequatable-t-not-made-contravariant-in-t-for-c-sharp-4-0)
     - [“Interface not implemented” when Returning Derived Type](https://stackoverflow.com/questions/1121283/interface-not-implemented-when-returning-derived-type)
     - [Does C# support return type covariance?](https://stackoverflow.com/questions/5709034/does-c-sharp-support-return-type-covariance)
     - [Why C# doesn't allow inheritance of return type when implementing an Interface](https://stackoverflow.com/questions/1319663/why-c-sharp-doesnt-allow-inheritance-of-return-type-when-implementing-an-interf)
     - [The return type of the members on an Interface Implementation must match exactly the interface definition?](https://stackoverflow.com/questions/7996127/the-return-type-of-the-members-on-an-interface-implementation-must-match-exactly)
     - [C# return type covariance and Liskov substitution principle](https://stackoverflow.com/questions/43892239/c-sharp-return-type-covariance-and-liskov-substitution-principle)
     - [What do you need Covariant Return Types for?](https://softwareengineering.stackexchange.com/questions/368872/what-do-you-need-covariant-return-types-for)
     - [C# covariant return types utilizing generics](https://stackoverflow.com/questions/4348760/c-sharp-covariant-return-types-utilizing-generics)
     
     
### 4. Gists
   - [HtmlAgilityPack Encapsulator Example](https://github.com/zzzprojects/html-agility-pack/blob/master/src/Tests/HtmlAgilityPack.Tests.NetStandard2_0/EncapsulatorTests.cs)
   - [Generic Equality Comparer for type T](https://gist.github.com/parsalotfy/3209ef2e71255773342b99cab9700f32)
   - [VSCode launch configuration for building and testing csharp code by pressing F5](https://gist.github.com/parsalotfy/10a466c0681fc14bdd86debee7e9789d)
   - [Example .gitignore file I use for C# projects](https://gist.github.com/kmorcinek/2710267)
   
   
### 5. Closures
   - [Jon Skeet](https://csharpindepth.com/Articles/Closures)
   - [Erik Lippert](https://ericlippert.com/2009/11/12/closing-over-the-loop-variable-considered-harmful-part-one/)
   - StackOverflow
     - [Captured variable in a loop in C#](https://stackoverflow.com/questions/271440/captured-variable-in-a-loop-in-c-sharp)
     - [Captured Closure (Loop Variable) in C# 5.0](https://stackoverflow.com/questions/16264289/captured-closure-loop-variable-in-c-sharp-5-0)
     - [Reference type variable recycling - is a new reference variable created every loop in a loop if declared therein?](https://stackoverflow.com/questions/7383016/reference-type-variable-recycling-is-a-new-reference-variable-created-every-lo)
     - [Is there a reason for C#'s reuse of the variable in a foreach?](https://stackoverflow.com/questions/8898925/is-there-a-reason-for-cs-reuse-of-the-variable-in-a-foreach)
     - [Is it better coding practice to define variables outside a foreach even though more verbose?](https://stackoverflow.com/questions/2388619/is-it-better-coding-practice-to-define-variables-outside-a-foreach-even-though-m)
     - [What is a closure?](https://softwareengineering.stackexchange.com/questions/40454/what-is-a-closure)
     - [What is a 'Closure'?](https://stackoverflow.com/questions/36636/what-is-a-closure)
     - [Starting Tasks In foreach Loop Uses Value of Last Item](https://stackoverflow.com/questions/4684320/starting-tasks-in-foreach-loop-uses-value-of-last-item)
     
### 6. Expression
   - Microsoft Docs
     - [Expressions](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/statements-expressions-operators/expressions)
     - [LambdaExpression](https://docs.microsoft.com/en-us/dotnet/api/system.linq.expressions.lambdaexpression?view=netframework-4.8)
     - [Expression TDelegate](https://docs.microsoft.com/en-us/dotnet/api/system.linq.expressions.expression-1?view=netframework-4.8)
     - [Expression Trees](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/expression-trees/)
   - Other Docs
     - [Geeks for Geeks](https://www.geeksforgeeks.org/expression-tree/) 
     - Marc Gravell
       - [Express yourself](https://blog.marcgravell.com/2008/10/express-yourself.html)
       - [Future Expressions](https://blog.marcgravell.com/2008/11/future-expressions.html)
   - Use Cases
     - [Expression as a Compiler](https://www.infoq.com/articles/expression-compiler/)
     - [Whats a good use case for .net 4.0 Expression Trees?](https://stackoverflow.com/questions/1532600/whats-a-good-use-case-for-net-4-0-expression-trees)
     - [Practical use of expression trees](https://stackoverflow.com/questions/403088/practical-use-of-expression-trees)
   - Comparison : Delegate, Lambada , Expression , Reflection
     - [Faster Reflection using Expression Trees](http://geekswithblogs.net/Madman/archive/2008/06/27/faster-reflection-using-expression-trees.aspx) 
     - [In C#, Is Expression API better than Reflection](https://stackoverflow.com/questions/4803272/in-c-is-expression-api-better-than-reflection)
     - [Delegate.CreateDelegate vs DynamicMethod vs Expression](https://stackoverflow.com/questions/597819/delegate-createdelegate-vs-dynamicmethod-vs-expression)
     - [Difference between expression lambda and statement lambda](https://stackoverflow.com/questions/17240642/difference-between-expression-lambda-and-statement-lambda)
     - [Moving from reflection to expression-tree](https://stackoverflow.com/questions/35913495/moving-from-reflection-to-expression-tree)
