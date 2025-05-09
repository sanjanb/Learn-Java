# Java File Extension Information

In Java, the `.java` extension is used for all code files.

- Every child (code file) you write **needs to have the `.java` extension**, which denotes a class.
- **Everything you write in Java is within a class**. This implies that all Java source code resides within `.java` files.
- There is a convention in Java where the **name of the class, specifically the `public` class, must be the same as the `.java` filename**. For instance, if you have a `public class Main`, the file must be named `Main.java`. If the filename and the `public` class name do not match, it will cause issues, although other non-public classes might be allowed.
- `.java` files are the **source code files**. They contain the human-readable Java code that you write.
- When you compile a `.java` file using the Java compiler (`javac`), it creates a **`.class` file**. The `.class` file contains the **bytecode**, which is the intermediate format that the Java Virtual Machine (JVM) can understand and execute. This compilation process allows the bytecode (`.class` file) to be run on any machine with a compatible JVM, regardless of the underlying operating system or hardware.
- `.java` files are often stored within **folders or packages**. These packages are essentially just folders that help organize files and provide rules for accessibility. The package structure, using dots (e.g., `com.राहुल.kunal`), reflects the folder hierarchy on the file system.
- Integrated Development Environments (IDEs) like IntelliJ IDEA automatically handle some of these conventions, such as creating `.java` files with the correct naming based on the class name.

## Interactive Questions

### Question 1

What extension is used for Java source code files?

- A) `.class`
- B) `.java`
- C) `.txt`

<details>
<summary>Answer</summary>
B) `.java`
</details>

### Question 2

What must match the filename of a `.java` file if it contains a `public` class?

- A) The name of any class in the file
- B) The name of the `public` class
- C) The name of the package

<details>
<summary>Answer</summary>
B) The name of the `public` class
</details>

### Exercise

Create a simple Java class named `HelloWorld` with a `main` method that prints "Hello, World!" to the console. Save it in a file named `HelloWorld.java`.

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

Compile and run the program to see the output.

### Reflection

- Why is it important for the filename to match the `public` class name in Java?
- What happens during the compilation of a `.java` file?
