# [WIP] Go Design Patterns

My own collection of Software Design Patterns written in Go (GoLang).  
For learning purposes: Some design patterns may not make sense when writing idiomatic Go.

## Classification

### Gang of Foud (GoF)

1. [Creational Patterns](#creational-patterns)
2. [Structural Patterns](#structural-patterns)
3. [Behavioral Patterns](#behavioral-patterns)

### Others

1. [Concurrency Patterns](#concurrency-patterns)
2. [Messaging Patterns](#messaging-patterns)

## Design Patterns

### Creational Patterns

| Pattern          | Description  | Gist |
| -----------------| ------------ | ---- |
| Abstract Factory | Provides an interface for creating families of related or dependent objects without specifying their concrete classes. | Todo |
| Builder          | Separate the construction of a complex object from its representation so that the same construction process can create different representations. | [Link](https://gist.github.com/maxclav/b982bfd7da5f4aa9f03bb5877c02b958) |
| Factory Method   | Define an interface for creating a single object, but let subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to subclasses. | [Link](https://gist.github.com/maxclav/0e5dd39ba014a4bcfd67fc10f6096d22) |
| Prototype        | Specify the kinds of objects to create using a prototypical instance and create new objects by copying this prototype. | [Link](https://gist.github.com/maxclav/b669496c49eea3c404c6dd529699e65d) |
| Singleton        | Ensure a class has only one instance, and provide a global point of access to it. | [Link](https://gist.github.com/maxclav/2200c92d3cf3ed362b90d1fae0bdd03f) |

### Structural Patterns

| Pattern   | Description  | Gist |
| --------- | ------------ | ---- |
| Adapter   | Convert the interface of a class into another interface that clients expect. Adapter lets classes work together that could not otherwise because of incompatible interfaces.. | Todo  |
| Bridge    | Decouple an abstraction from its implementation so that the two can vary independently. | Todo  |
| Composite | Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly. | Todo  |
| Decorator | Attach additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality. | Todo  |
| Facade    | Provide a unified interface to a set of interfaces in a subsystem. Facade define a higher level interface that makes the subsystem easier to use. | Todo  |
| Flyweight | Use sharing to support large numbers of fine grained objects efficiently. | Todo  |
| Proxy     | Provide a surrogate or placeholder for another object to control access to it. | Todo  |

### Behavioral Patterns

| Pattern                 | Description  | Gist |
| ----------------------- | ------------ | ---- |
| Chain of Responsibility | Avoir coupling the sender of a request to its receiver by giving more than one object a chance to handle the request. | Todo  |
| Command                 | Encapsulate a request as an object, thereby letting you parameterize clients with different requests, queue or log requests, and support undoable operations. | Todo  |
| Interpreter             | Given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language. | Todo  |
| Iterator                | Provide a way to access the elements of an aggregate objects sequentially without exposing its underlying representation. | Todo  |
| Mediator                | Define an object that encapsulates how a set of objects interact. | Todo  |
| Memento                 | Without violating encapsulation, capture and externalize an object's internal state to that the object can be restored to this state later. | Todo  |
| Observer                | Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically. | Todo  |
| State                   | Allow an object to alter its behavior when its internal state changes. The object will appear to change its class. | Todo  |
| Strategy                | Define a family of algorithms, encapsulate each one, and make them interchangeable.. | Todo  |
| Template Method         | Define the skeleton of an algorithm in an operation, deferring some steps to subclasses. | Todo  |
| Visitor                 | Represent an operation to be performed in the elements of an object structure. | Todo  |

### Concurrency Patterns

Todo

### Messaging Patterns

Todo

## Resources

### Books

1. <https://www.oreilly.com/library/view/design-patterns-elements/0201633612/>
2. <https://www.oreilly.com/library/view/code-complete-2nd/0735619670/>

### Github

1. <https://github.com/kamranahmedse/design-patterns-for-humans>
2. <https://github.com/tmrts/go-patterns>
3. <https://github.com/DovAmir/awesome-design-patterns>

### Other Resources

1. <https://refactoring.guru/design-patterns/go>
2. <https://en.wikipedia.org/wiki/Software_design_pattern#>
