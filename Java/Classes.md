- we should define each class in its own file for good practice.
- we use packages to seperate classes for readability
- a class is blueprint and object is an instance of that blueprint.
```java
class ClassName {
	// Fields
	int bro = 5;

	// Methods
	public void bruh {
		System.out.println(bro);
	}
}
```
- [[Fields]] are variables and methods are functions like operations.
- if we want to execute a function in a class without creating an instance of it, we declare said function as "**static**"
- we can access static methods directly from the class like: "ClassName.staticMethod();"