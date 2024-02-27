# Module
Python
````Python
~~~
#Module basic(thường)
def printmultiply(n, f):
    if not isinstance(n, (int, float)) or not isinstance(f, (int, float)):
        raise TypeError("Vui lòng nhập số cho n và f")
    total = n * f
    print(total)

def printdivide(n, f):
    if not isinstance(n, (int, float)) or not isinstance(f, (int, float)):
        raise TypeError("Vui lòng nhập số cho n và f")
    if f == 0:
        raise ValueError("Không thể chia cho 0")
    total = n / f
    print(total)

def printmodulo(n, f):
    if not isinstance(n, (int, float)) or not isinstance(f, (int, float)):
        raise TypeError("Vui lòng nhập số cho n và f")
    total = n % f
    print(total)
def printadd(n, f):
    if not isinstance(n, (int, float)) or not isinstance(f, (int, float)):
        raise TypeError("Vui lòng nhập số cho n và f")
    total = n + f
    print(total)

def printabate(n, f):
    if not isinstance(n, (int, float)) or not isinstance(f, (int, float)):
        raise TypeError("Vui lòng nhập số cho n và f")
    total = n - f
    print(total)
~~~
