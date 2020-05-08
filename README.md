# Factory Method Pattern C# Example
Simple example of the Factory Method Pattern implementation with C#

## Definition
Define an interface for creating an object, but let subclasses decide which class to instantiate.

<dl>
  <dt>Product</dt>
  <dd>Defines the interface of objects that the factory methods creates.</dd>
  <dt>ConcreteProduct</dt>
  <dd>Implements the Product interface.</dd>
  <dt>Creator</dt>
  <dd>Abstract class the declares the abstract Factory Method, wich returns an object of Product.</dd>
  <dt>ConcreteCreator</dt>
  <dd>Implements the Creator abstract class and overrides the Factory method to return an instance of Concrete product.</dd>
</dl>
