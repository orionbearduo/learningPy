# VARIABLES AND SIMPLE DATA TYPES

## Variables
A Python variable is a symbolic name that is a reference or pointer to an object.
Once an object is assigned to a variable, you can refer to the object by that name.
就像人的名字一样

```python
message = "Hello Python world!"
print(message)

message = "Hello Python Crash Course world!"
print(message)
```

## Naming and Using Variables

When you’re using variables in Python, you need to adhere to a few rules and guidelines. Breaking some of these rules will cause errors; other guidelines just help you write code that’s easier to read and understand. Be sure to keep the following variable rules in mind:

1. Variable names can contain only letters, numbers, and underscores. They can start with a letter or an underscore, but not with a number. For instance, you can call a variable message_1 but not 1_message.
2. Spaces are not allowed in variable names, but underscores can be used to separate words in variable names. For example, greeting_message works, but greeting message will cause errors.
3. Avoid using Python keywords and function names as variable names; that is, do not use words that Python has reserved for a particular programmatic purpose, such as the word print.
4. Variable names should be short but descriptive. For example, name is better than n, student_name is better than s_n, and name_length is better than length_of_persons_name.
5. Be careful when using the lowercase letter l and the uppercase letter O because they could be confused with the numbers 1 and 0.

It can take some practice to learn how to create good variable names, especially as your programs become more interesting and complicated. As you write more programs and start to read through other people’s code, you’ll get better at coming up with meaningful names.

## Variables Are Labels

Variables are often described as boxes you can store values in. This idea can be helpful the first few times you use a variable, but it isn’t an accurate way to describe how variables are represented internally in Python. It’s much better to think of variables as labels that you can assign to values. You can also say that a variable references a certain value.

# TRY IT YOURSELF(homework)

1. Simple Message: Assign a message to a variable, and then print that message.

2. Simple Messages: Assign a message to a variable, and print that message. Then change the value of the variable to a new message, and print the new message.