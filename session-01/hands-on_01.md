# Hands-on 01

> This is a guide for the hands-on in Session 1 of the Python workshop.

Open a new notebook, and explain what it is. Try changing name.

Variable: Variables are the names you give to computer memory locations which are used to store values in a computer program. In Python, you declare a variable by assigning a value to it using the assignment operator (=).

```py
hello_message = 'Welcome to the Python workshop!'
```

Shift + Enter for typing it out. Nothing is returned. Let's see the value of the variable.

```py
hello_message
```

We can also perform calculations in here.

```py
3 + 4
```

Strings (words) can be concatenated as if we were performing the sum operation.

```py
hello_message + ' Thank you for being here!'
```

However, the value of the variable is unchanged.

```py
hello_message
```

We can change the value of the variable by assigning it again.

```py
hello_message = hello_message + ' Thank you for being here!'
```

Let's see it changes.

```py
hello_message
```

There's a shorthand for this notation.

```
# a = a + b
# equivalent to:
# a += b
hello_message += ' You\'re awesome!'
```

Look! We made a comment before. Explain the `\`. And the variable has changed:

```py
hello_message
```

Let's now focus a bit more on the notebook. See here it says 'Code'. We can try changing the block to 'Markdown'. Now, we can write notes. This is extremely useful.

```md
This is an **example** of a Markdown note.
```

Markdown is a simple markup language in which you can format your text really easily, for example:

```md
Text can be **bold**, _italic_ or you can even `write_code()`.

You can

1. also
2. make
3. lists

> And way more!
```

Show how to delete and add cells, and how to change the type of cell. Finally, we will show one final thing: the `print` and the `input` statements.

When we are programming in Python and we want to show something in the console, we need to use the `print` statement.

```py
print('This is a message printed on the console')
```

We can actually embed variables into strings easily.

```py
print(f'This is the value of hello_message: {hello_message} -- You see?')
```

We use `input` to ask for values from the console.

```py
result = input('Insert a value here: ')
```

Let's see the value stored in result:

```py
result
```

We could try and print this value:

```py
print(result)
```

Finally, one thing to clarify: the difference between `print(x)` and putting only `x` in Jupyter Notebook.

- In the first case, we are actually printing something out. This works also outside of Jupyter Notebook.
- In the second case, we are only showing the value because it is Jupyter Notebook's behavior. Look at how the string is enclosed in `''`. You will know more about strings in the next session.

```py
print(hello_message)
```

```py
hello_message
```
