### Day 1 - Beginner - Working with Variables in Python to Manage Data
---
---
In Python, the `print()` statement is used to display output to the console or terminal. It takes one or more arguments, which can be of any data type, and prints them to the standard output. Here's a basic example:

```Python
print("Hello, world!")
```

This would output "Hello, world!" to the console.

You can also print multiple values by separating them with commas:

```Python
name = "John" 
age = 30 
print("Name:", name, "Age:", age)
```

This would output "Name: John Age: 30" to the console.

In Python 3.x, `print()` is a function, so it requires parentheses around its arguments, whereas in Python 2.x, it was a statement and didn't require parentheses.

----
##### Single vs Double Quote
---
In Python, both single (`'`) and double (`"`) quotes can be used to define string literals. There is no functional difference between them; both can be used interchangeably to create strings. However, they can be useful in different situations:

1. **String Quoting**: If your string itself contains a single quote, you might want to use double quotes to define the string, and vice versa. For example:
```Python
single_quoted = 'She said, "Hello!"' 
double_quoted = "It's raining outside."
```

2. Using double quotes for the first string makes it easier to include the single quote inside the string without escaping it, and using single quotes for the second string makes it easier to include the apostrophe.

In general, the choice between single and double quotes often comes down to personal preference or coding style conventions. It's important to maintain consistency within a codebase.