# References
1. https://medium.com/@ongchengjie/understanding-scalas-trait-and-stackable-traits-pattern-with-java-eb4e8730e3b4
2. https://github.com/alexandru/scala-best-practices


# Concepts
1. functional programming support
   1. functions as first class citizens: pass as arg, return as val, assign to variable
   2. higher order functions: pass funciton inside other function, return function
   3. Partially Applied Functions
2. immutability of objects and collections
3. lazy eval
4. Functions: resusable code when we don't need explicity define OO state and behaviour
   1. internally objects of trait Function1/FunctionN with apply method
   2. () calls the apply method behind the scenes
5. Methods: behaviour exposed within class body
6. Java interface versus scala trait
   1. java interface is about publically exposed logic
   2. scala trait is about reusable logic to be mixin with classes and also dynamically with objects
