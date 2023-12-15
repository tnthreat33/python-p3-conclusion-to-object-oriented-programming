# Conclusion to Object-Oriented Programming Basics

## Learning Goals

- Build robust and dynamic Python objects.
- Accomplish complex programming tasks using knowledge from previous modules..

***

## Key Vocab

- **Class**: a bundle of data and functionality. Can be copied and modified to
accomplish a wide variety of programming tasks.
- **Initialize**: create a working copy of a class using its `__init__()`
method.
- **Instance**: one specific working copy of a class. It is created when a
class's `__init__()` method is called.
- **Object**: the more common name for an instance. The two can usually be used
interchangeably.
- **Object-Oriented Programming**: programming that is oriented around data
(made mobile and changeable in **objects**) rather than functionality. Python
is an object-oriented programming language.
- **Procedural Programming**: programming that is oriented around procedures
that are called in sequential order. Fortran and C are procedural programming
languages.
- **Function**: a series of steps that create, transform, and move data.
- **Method**: a function that is defined inside of a class.
- **Magic Method**: a special type of method in Python that starts and ends
with double underscores. These methods are called on objects under certain
conditions without needing to use their names explicitly. Also called **dunder
methods** (for **d**ouble **under**score).
- **Attribute**: variables that belong to an object.
- **Property**: attributes that are controlled by methods.

***

## Conclusion

Now we should have a basic grasp on object-oriented programming. As discussed
in this section, we should have an understanding of the concept of "objects"
that can contain data and/or code, such as attributes and methods.

In this section we explained the concept of class and instance variables, as
well as instance methods. We learned about creating properties using Python's
built-in `property()` function, as well as how to dynamically manipulate
attributes using `attr()` functions. We can now set instance attributes from
the `__init__` magic method at the same time as we instantiate objects using
the `self` keyword.

What we will be able to achieve is shared functionality throughout the
application as needed. You're well on our way to having enough knowledge of OOP
to develop your own fully functional applications!

***

## Resources

- [Python documentation][python docs]
- [Classes - Python Documentation](https://docs.python.org/3/tutorial/classes.html)
- [Object-Oriented Programming (OOP) in Python 3 - Real Python](https://realpython.com/python3-object-oriented-programming/)
- [Differences Between Procedural and Object-Oriented Programming - GeeksforGeeks](https://www.geeksforgeeks.org/differences-between-procedural-and-object-oriented-programming/#:~:text=Object%2Doriented%20programming%20is%20based,the%20concept%20of%20procedure%20abstraction.)

[python docs]: https://docs.python.org/3/
