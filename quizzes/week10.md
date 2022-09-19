# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Provides a scope for the identifiers

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
a class is a user defined blueprint while a struct is a collection of various different data types under a unit

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
The void method

```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Car.Start()

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
This class has a return type of string,

```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```

The creation of a object

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```

Allows for the class to be overridden

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```

private, public, abstract, internal

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only by types derived from the class

```