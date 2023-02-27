# golang-for-programmers-educative
My solutions to skill path "Golang For Programmers" on educative.io

## Module 1: Getting Started with Golang

### Origin, Context and Popularity of Go(notes)

The main goal of Go programming language is to combine the good parts of statically typed and dynamically typed languages to make programmiong more fun

* efficacy
* speed
* safety
* ease of programming

Go programming language is famous for its building speed, and is very suitable to write network applications and those which benefit from concurrency and parallelization. Go is also a functional programming language, its functions are first-class elements, we can apply a variety of functional programming skills.

Go has a lot of application scenarios such as system programming, general programming, gaming and IoT development.

### Basic Constructs and Elementary Data Types

The filename of go sources are usually in lower case, if it consists of multi words, then they are connected with underscores like educative_platform.go.

Within a package all source files are compiled together as a unit. By convention each directory contains a package. The

Use `import` to load the packages to be ready in use. `import` only loads the public declarations. Identifiers that start with lowercase letters are internal, otherwise are external.

In Go, smaller functions can be written in one line. Clear and readable source codes are a major goal for this programming language.

The default value of a composite type except struct is nil. The type of function is the type of variable returned by it.

A constant can be only in type of boolean, number and string. A newly created const block will set `iota` back to 0 again.

Go compiler can infer the variable type from the value, it is called automatic type inference.

In Go, a global scope is equal to a package scope. An identifier with global scope can be seen in all sources of the same package.

All variables of elementary type are all value types, which are allocated on stack. All structured types are reference types, for example: chan, map, slice, which are allocated on heap and garbage-collected.

Use float64 whenever possible, because math package uses it a lot.

Go string is a sequence of variable-width characters (1-4 bytes), and is immutable arrays of bytes.


