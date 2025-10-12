# Java Language
General presentation of Java language.

I have been working with Java language for a while and for big companies.
A very frustating issue is in big companies you are always late.
You still use Java 4 whereas Java 5 exists.
You still use Java 8 whereas Java 25 is available...

## Online compiler
There are several online compiler available
* https://www.programiz.com/java-programming/online-compiler/
  * Actually several language are available (Python)
    * Java 21
    * No Junit 
* https://www.w3schools.com/java/tryjava.asp?filename=demo_compiler
  * I really prefer this one.
    * Java 14
    * Junit (4.13) is available
* https://www.jdoodle.com/online-java-compiler
  * Java 21
  * No Junit
* https://www.onlinegdb.com/online_java_compiler
  * Java 21
  * No Junit
 
I didn't find any support of Junit5. But for very simple examples Junit4 is may be enough.

## Java Key word
### final
The final variable can be assigned only once.

### default
* in switch statement
* default implementation in an interface

### enum
It has been introduced in Java version 5.
This is a special class regrouping several constants.

### var
It has been introduced in Java version 10.
Var is not a "Java key word" but a reserved type name.
It let the compiler detect the type following the context.


## Java type and classes
### Boxed type
In java all primitive type like int has a boxed type a class. 
* for int this is Integer.
* for long this is Long.

### Optional
Optional has been introducted in Java8 and is also used with the Stream (return in the min and max).

## Java lambda and stream
Java Stream and lambda have been introduced in Java 8.

### Functional interface
* Predicate<T> arguments T, returns boolenan
* Consumer<T> arguments T, returns void
* Function<T,R> arguments T, returns R
* Supplier<T> arguments None, returns T
* UnitaryOperator<T> arguments T, returns T
* BinaryOperator<T> arguments (T,T), returns T

### Stream operations
* collect
* map (type convertion)
* filter
* flatmap
* min max (return an Optional)
* reduce (accumulator)

## References
### Books
* Java 8 Lambdas functional programming for the masses (Richard Warburton)


