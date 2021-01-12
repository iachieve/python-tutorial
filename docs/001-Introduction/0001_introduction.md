---
layout: default
title: Introduction
nav_order: 10
has_children: false
permalink: python-tutorial/Introduction
---

# Installation Guide
- [How to install python on mac](https://www.python.org/downloads/mac-osx/)
- [How to install python on windows](https://www.python.org/downloads/windows/)
- [Download IntelliJ IDEA](https://www.jetbrains.com/idea/download/#section=mac)
---
# Introduction
- how to run code cmd/ctrl + r
```python
print("hello world")
print("Hello", "World", sep='-')
```
- Python Indentation

```python
if 5 > 2:
    print("Five is greater than two!")
if 1 == 1:
    print("correct")
```
---
---
layout: default
title: Introduction
nav_order: 15
has_children: false
permalink: python-tutorial/Introduction
---
# Comments
- Comments can be used to explain Python code.
- Comments can be used to make the code more readable.
- Comments can be used to prevent execution when testing code.
- Comment keyboard shortcut ( cmd + / )
```python
 #This is a comment 
print("Hello, World!") 
```
-   Comments can be placed at the end of a line, and Python will ignore the rest of the line
 ```python
print("Hello, World!") #This is a comment 
```
-   Comments does not have to be text to explain the code, it can also be used to prevent Python from executing code.
```python
 #print("Hello, World!") 
print("Cheers, Mate!") 
```

---
# Multi Line Comments
```python
#This is a comment 
#written in 
#more than just one line 
print("Hello, World!") 
 
""" 
    This is a comment 
     written in 
    more than just one line 
""" 
print("Hello, World!") 
```

