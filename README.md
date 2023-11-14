# 0x00. AirBnB clone - The console

Concepts
For this project, we expect you to look at these concepts:

- [Python packages](https://intranet.alxswe.com/concepts/66)
- [AirBnB clone](https://intranet.alxswe.com/concepts/74)

<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/263/HBTN-hbnb-Final.png" width="1500" height="300">

# Background Context

## Welcome to the AirBnB clone project!

Before starting, please read the AirBnB concept page.

## First step: Write a command interpreter to manage your AirBnB objects.

This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

- put in place a parent class (called BaseModel) to take care of the initialization, - serialization and deserialization of your future instances
- create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON - string <-> file
- create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
- create the first abstracted storage engine of the project: File storage.
- create all unittests to validate all our classes and storage engine

## What’s a command interpreter?

Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object

# Resources

### Read or watch:

- [cmd module](https://docs.python.org/3.8/library/cmd.html)
- [cmd module in depth](http://pymotw.com/2/cmd/)
- **_packages concept page_**
- [uuid module](https://docs.python.org/3.8/library/uuid.html)
- [datetime](https://docs.python.org/3.8/library/datetime.html)
- [unittest module](https://docs.python.org/3.8/library/unittest.html#module-unittest)
- [args/kwargs](https://yasoob.me/2013/08/04/args-and-kwargs-in-python-explained/)
- [Python test cheatsheet](https://www.pythonsheets.com/notes/python-tests.html)
- [cmd module wiki page](https://wiki.python.org/moin/CmdModule)
- [python unittest](https://realpython.com/python-testing/)

## Purpose
<img src="https://camo.githubusercontent.com/97788fc5310cea2961d9d8dbfa9cb4b6aacd420eb1efb27372af451d7f04b7a7/68747470733a2f2f692e696d6775722e636f6d2f6f764d4e79455a2e706e67" width="1500" height="300">
The purpose of this project is to understand how to:   
* create a Python package   
* create a command interpreter using the `cmd` module   
* serialize and deserialize a Class   
* write and read a JSON file   
* manage `datetime`   
* use `*args` and `**kwargs`   
* handle named arguments in a function

### HTML and CSS concepts

Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive!

Before developing a big and complex web application, we will build the front end step-by-step.

The first step is to “design” / “sketch” / “prototype” each element:

- Create simple HTML static pages
- Style guide
- Fake contents
- No Javascript
- No data loaded from anything

During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be the first thing to write. CSS is the styling of your page, the design. I really encourage you to fix your HTML part before starting the styling. Indeed, without any structure, you can’t apply any design.

## Learning Objectives

- What is `HTML`
- How to create an `HTML page`
- What is a `markup language`
- What is the `DOM`
- What is an `element / tag`
- What is an attribute
- How does the browser load a webpage
- What is `CSS`
- How to add style to an element
- What is a `class`
- What is a `selector`
- How to compute `CSS Specificity Value`
- What are `Box properties` in `CSS`

## Requirements

### PYTHON SCRIPT REQUIREMENTS  
   * allowed editors: `vi`, `vim`, `emacs`   
   * the first line of all files should be exactly `#!/usr/bin/python3`   
   * all code should use the `PEP8` style (version 1.7.*)   
   * all files must be executable   
   * all files will be interpreted/compiled on Ubuntu 14.04 LTS using `python3` (version 3.4.3)   

### PYTHON TEST CASE REQUIREMENTS    
   * all test files should be in the folder `tests`   
   * all test files should be text files (extension: `.txt`)   
   * all test files should be executed using the command `python3 -m doctest ./tests/*`   
   * all modules should have documentation `python3 -c 'print(__import__("my_module").__doc__)'`   
   * all functions (inside and outside of classes) should have documentation `python3 -c 'print(__import__("my_module").my_funct\
ion.__doc__)'`   

### General

- Allowed editors: `vi`, `vim`, `emacs`
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should be `W3C compliant` and validate with `W3C-Validator`
- All your CSS files should be in styles folder
- All your images should be in images folder
- You are not allowed to use `!important` and `id (#... in the CSS file)`
- You are not allowed to use tags `img`, `embed` and `iframe`
- You are not allowed to use `Javascript`
- Current screenshots have been done on Chrome 56 or more.
- No cross browsers
- You have to follow all requirements but some margin/padding are missing - you should try to fit as much as you can to screenshots   

## Usage Examples for console

### Interactive Mode

```python3
~/me$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
~/me$
```

### Non-Interactive Mode

```python3
~/me$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)

~/me$ cat test_help
help
~/me$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
~/me$
```

## Bugs

At this time, there are no known bugs.

## License

**AirBnB Clone** is open source and free to download and use

## Author
@ [Kenrique Ngwa](https://github.com/kenrique100)
@ [ Palesa Monareng](https://github.com/Mbarleesah)

