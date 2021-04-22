## Unlocking tests  

```bash
espeon@Espeon:~/work/cs61a/lab00$ python3 ok -q python-basics -u
=====================================================================
Assignment: Lab 0
OK, version v1.15.0
=====================================================================

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Unlocking tests

At each "? ", type what you would expect the output to be.
Type exit() to quit

---------------------------------------------------------------------
Python Basics > Suite 1 > Case 1
(cases remaining: 2)

What would Python display? If you get stuck, try it out in the Python
interpreter!

>>> 10 + 2
? 12
-- OK! --

>>> 7 / 2
? 3.5
-- OK! --

>>> 7 // 2
? 3
-- OK! --

>>> 7 % 2                       # 7 modulo 2, equivalent to the remainder of 7 // 2
? 1
-- OK! --

---------------------------------------------------------------------
Python Basics > Suite 2 > Case 1
(cases remaining: 1)

What would Python display? If you get stuck, try it out in the Python
interpreter!

>>> x = 20
>>> x + 2
? 22
-- OK! --

>>> x
? 20
-- OK! --

>>> y = 5
>>> y += 3                      # Equivalent to y = y + 3
>>> y * 2
? 16
-- OK! --

>>> y //= 4                     # Equivalent to y = y // 4
>>> y + x
? 22
-- OK! --

---------------------------------------------------------------------
OK! All cases for Python Basics unlocked.

Backup... 100% complete
```  

## Understanding problems  

This section is to ask us to appoint the return value an arithmetic expression that evaluates to 2020.  

```python
def twenty_twenty():
    """Come up with the most creative expression that evaluates to 2020,
    using only numbers and the +, *, and - operators.

    >>> twenty_twenty()
    2020
    """
    return 100*20+20
```

100*20+20 would be nice.  

```bash
espeon@Espeon:~/work/cs61a/lab00$ python3 ok
=====================================================================
Assignment: Lab 0
OK, version v1.15.0
=====================================================================

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Running tests

---------------------------------------------------------------------
Test summary
    3 test cases passed! No cases failed.

Backup... 100% complete
```