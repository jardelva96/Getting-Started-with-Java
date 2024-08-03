# Getting Started with Java

Java is a popular, high-level programming language known for its portability, performance, and robustness. It is widely used in various applications, from web development to mobile apps and large-scale enterprise systems. This article will introduce you to the basics of Java, including its syntax, data types, and object-oriented programming principles.

## What is Java?

Java is a class-based, object-oriented programming language developed by Sun Microsystems (now owned by Oracle Corporation). Java applications are compiled into bytecode that can run on any Java Virtual Machine (JVM), making them platform-independent.

## Basic Syntax

### Hello World Program

A simple Java program to print "Hello, World!" to the console:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
## Variables and Data Types
Java supports various data types, including integers, floating-point numbers, characters, and booleans. Here's how to declare and use variables in Java:

```java
public class DataTypes {
    public static void main(String[] args) {
        int myNumber = 5;            // Integer
        double myDouble = 5.99;      // Floating point number
        char myLetter = 'D';         // Character
        boolean myBool = true;       // Boolean
        String myText = "Hello";     // String
    }
}
```
## Control Flow
Java provides several control flow statements for decision making and looping:

## If-Else Statement
```
```java
public class IfElse {
    public static void main(String[] args) {
        int x = 20;
        if (x > 10) {
            System.out.println("x is greater than 10");
        } else {
            System.out.println("x is less than or equal to 10");
        }
    }
}
```
## For Loop
```java
public class ForLoop {
    public static void main(String[] args) {
        for (int i = 0; i < 5; i++) {
            System.out.println(i);
        }
    }
}
```
## Object-Oriented Programming
Java is an object-oriented programming (OOP) language. Key OOP concepts include classes, objects, inheritance, and polymorphism.

## Classes and Objects
A class is a blueprint for creating objects. An object is an instance of a class.

```java
public class Dog {
    String breed;
    int age;
    String color;

    void barking() {
        System.out.println("Woof!");
    }

    void hungry() {
        System.out.println("I'm hungry!");
    }

    void sleeping() {
        System.out.println("Zzz...");
    }
}
```
## Creating Objects
```java
public class Main {
    public static void main(String[] args) {
        Dog myDog = new Dog(); // Create a Dog object
        myDog.breed = "Labrador";
        myDog.age = 5;
        myDog.color = "Black";
        myDog.barking();
    }
}
```
# Conclusion
Java is a versatile and powerful programming language that is widely used across various domains. By understanding the basics of Java syntax, data types, control flow, and object-oriented programming, you can start building your own Java applications. As you dive deeper into Java, you'll discover more advanced features and libraries that will help you create robust and scalable applications.
