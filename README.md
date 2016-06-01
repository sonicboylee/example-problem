# Example Problem Set

This is a demonstration problem set, showing
how we can write a skeleton problem for our
students.

## Instructions

- [ ] Complete the troll_count function according to the instructions.

To check your code works, you can run it and then call `run_tests()`. If
you get no output, it means all your code works!

## Notes

This problem involves the use of conditionals. The syntax for any
conditional in python looks like:

``` python
if some criteria:
	do something
```

If we are dealing with integers, the criteria we could use include:

* `==` - equals
* `>=` - greater than or equal to
* `<` - less than

For example:

``` python
if x > 5:
	print("Greater than 5!")

if x <= 12:
	print("Less than or equal to 12")

if x == 2:
	print("2 exactly")
```

If we would like to check for multiple, mutually-exclusive conditions,
we can use `if`, `elif` and `else`:

``` python

if x > 10:
	print("Bigger than 10")
elif x < 2:
	print("Less than 2")
else:
	print("All other options - in this case between 2 and 10")
```
