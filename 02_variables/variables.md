# Numbers

Type the following variables into the REPL.

```python
a = 12
b = 5
c = 0.6
d = 17.1
```

You can start the REPL by typing `python` at the command line prompt. Then type the input at the Python prompt, like this:

<img src="img/repl.png" alt="" width=609 height=120 title="Python REPL"></img>

Read through the following expressions and predict the _value_ and _data type_ of each one - e.g. is it a string, an integer, a float?

Justify your prediction and then use Python to check if you were correct. You can use the `type` command to help: eg:

```python
type(a * b)
```

Make sure you understand why you got the results you did and investigate any that surprised you. You can use the [Python documentation](https://docs.python.org/3/).
[Speedsheet](https://speedsheet.io/s/python) for Python is also useful for quick reference.

A: 60 int

```python
a * b
```

B: 3 float

```python
b * c
```

C:5.6 float

```python
b + c
```

D:-29.1 float

```python
d - a
```

E:2 int

```python
a % b
```

F:2.0 float

```python
a % 5.0
```

G:25 int

```python
b**2
```

H:17 int

```python
a + b
```

I:0.41666 int

```python
b / a
```

J: 2 int

```python
a // b
```

K:16 int

```python
len('northcoders') + b
```

# Strings

In the Python REPL, create the following string variables:

```bash
>>> tutor = 'david john bartlett'

>>> title = 'Mr'

>>> job_title = "Senior Tutor"

```

You can see what _methods_ are available for strings in the [documentation](https://docs.python.org/3/library/stdtypes.html#text-sequence-type-str)
but you might find it easier to check out [SpeedSheet](https://speedsheet.io/s/python?q=strings-only#T7xJ). Use _string methods_ to create:

A. A new variable called `shouty_name` with value `DAVID JOHN BARTLETT`

B. A new variable called `low_key_title` with value `mr`

C. A new variable called `low_key_job_title` with value `senior tutor`

D. A new variable called `low_key_full_honours` with value `mr david john bartlett senior tutor`

For getting _parts_ of strings, check out [substrings and slicing](https://speedsheet.io/s/python?q=strings-only#nXRd)

Then try to create:

E: A new variable called `first_name` with value `david`

F: A new variable called `surname` with value `bartlett`

G: A new variable called `middle_name` with value `john`

H: A new variable called `full_honours` with value `Mr David John Bartlett, Senior Tutor`. (Note the comma!)

Note: it's easy to create brand new variables by just typing them in. For example:

```python
shouty_name = 'DAVID JOHN BARTLETT'
```

Please do not do this. The purpose of this exercise is to **create new variables from the original ones**.

# Booleans

Read through the following expressions and predict the value and data type of each one.

Justify your prediction and then type them into the Python REPL to check if you were correct.

Make sure you understand why you got the results you did and investigate any that surprise you.

A: True bool

```
30 > 12
```

B: False bool

```
4 < 4
```

C: false bool

```
12 == '12'
```

D: false bool

```
7 < 7.0
```

E: true bool

```
1 == True
```

F: true bool

```
0.9 < True
```

G: true bool

```
14 > 5 and len('tree') == 8/2
```

H: 4 and int - 3 is truthy so return 4

```
3 and 4
```

I: 0 and int - 3 is truthy so return 0

```
3 and 0
```

J: 0 and int - 0 is falsey so return 0

```
0 and 3
```

K: 3>4 is false or 5>2 is true - return true - bool 

```
3 > 4 or 5 > 2
```

L: 5 is true so return 5 - int

```
5 or 0.7
```

M: 4 int - 5>10 is falsey

```
5 > 10 or 4
```

N: false bool

```
not 10 > 5
```

O: true bool

```
not 10 < 5
```

P:
 false bool
```
not 3
```
