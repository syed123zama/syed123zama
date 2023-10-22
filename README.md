# # STRING DATATYPE
#
# a = "Hello, world" # This is a comments
# print(a)
# print(type(a))
#
# # NUMERIC DATATYPE
#
# x = 12
# print(x)
# print(type(x))
#
# y = 10.0
# print(y)
# print(type(y)
#       )
#
# z = complex(2, 6)
# print(z)
# print(type(z)
#       )
#
# # SEQUENCE DATATYPE
#
# x = ["Apple", "Banana", "Cherry"]
# print(x)
# print(type(x)
#       )
#
# y = ("Apple", "Banana", "Cherry")
# print(y)
# print(type(y)
#       )
#
# z = range(6)
# print(z)
# print(type(z)
#       )
#
# # MAPPING DATATYPE
#
# x = {"Apple": 2, "Banana": 3}
# print(x)
# print(type(x))
#
# # SET DATATYPE
#
# a = {"Apple", "Banana", "Cherry"}
# print(a)
# print(type(a)
#       )
#
# x = ({"Apple", "Banana", "Cherry"})
# print(x)
# print(type(x))
#
# # BOOLEAN DATATYPE
#
# y = True
# print(y)
# print(type(y))
#
# z = False
# print(z)
# print(type(z))
#
# x = b"Hello"
# print(x)
# print(type(x)
#       )
# x = bytearray(10)
# print(x)
# print(type(x))
#
# x = memoryview(bytes(10))
# print(x)
# print(type(x))
#
# y = None
# print(y)
# print(type(y)
#       )
#
# a = "Hello, world"
# print(a[2:6])
#
# b = "Hello, world"
# print(b[-5:-1])
#
# a = "Hello, world"
# print(a.upper())
#
# b = "Hello, world"
# print(b.lower())
#
# c = "Hello, world"
# print(c.replace("H", "J"))
#
# d = "Hello, world"
# print(d.split())
#
# a = "Hello "
# b = "World"
# c = (a + b)
# print(c)
#
# print("Hello,\n world")
# print("Hello,\t world")
# print("Hello,\b world")
# print("Hello,\r world")
# print("Hello,\\ world")
# print("Hello,\' world")
# print("Hello\" world")
# print("Hello,\f world")
# print("Hello,\ooo world")
#
# x = "Hello, world"
# print(len(x))
#
# print(10 > 9)
# print(10 == 9)
# print(10 > 9)
#
# a = 200
# b = 85
#
# if b > a:
#     print("b is greater than a")
# else:
#     print("b  isn't greater than a")
#
# print(bool("Hello"))
# print(bool(15))
#
# x = "Hello"
# y = 18
#
# print(bool(x)
#       )
# print(bool(y)
#       )
#
# print(bool(123))
# print(bool("abc"
#      ))
# print(bool(["Apple", "Banana", "Orange"]))
#
# def myfunc():
#     return False
#
# print(myfunc())
#
# def myfunc():
#     return True
#
# if myfunc():
#     print("Yes")
# else:
#     print("No")
#
# # ARITHMETIC OPERATORS
#
# a = 10
# b = 10
# c = a + b
# print(c)
#
# a = 10
# b = 8
# c = a - b
# print(c)
#
# a = 10
# b = 10
# c = a * b
# print(c)
#
# a = 10
# b = 2
# c = a / b
# print(c)
#
# a = 10
# b = 10
# c = a // b
# print(c)
#
# a = 10
# b = 10
# c = a ** b
#
# a = 10
# b = 10
# c = a % b
# print(c)
#
# # ASSIGNMENT OPERATORS
#
# a = 5
# a += 4
# print(a)
#
# a = 20
# a -= 5
# print(a)
#
# a = 20
# a *= 5
# print(a)
#
# a = 20
# a /= 5
# print(a)
#
# a = 20
# a %= 5
# print(a)
#
# a = 20
# a //= 5
# print(a)
#
# a = 20
# a **= 5
# print(a)
#
# a = 20
# a &= 5
# print(a)
#
# a = 20
# a |= 5
# print(a)
#
# a = 20
# a ^= 5
# print(a)
#
# a = 20
# a >>= 5
# print(a)
#
# a = 20
# a <<= 5
# print(a)

# COMPARISON OPERATOR

# x = 5
# y = 3
# print(x == y)
#
# x = 5
# y = 3
# print(x != y)
#
# x = 5
# y = 3
# print(x > y)
#
# x = 5
# y = 3
# print(x < y)
#
# x = 5
# y = 3
# print(x >= y)
#
# x = 5
# y = 3
# print(x <= y)
#
# # LOGICAL OPERATOR
#
# x = 5
# print(x > 3 and x < 10)
#
# x = 5
# print(x > 3 or x < 10)
#
# x = 5
# print(not(x < 5 and x < 10))
#
# print((6 + 3) - (6 + 3))
# print((6 - 3) + (6 - 3))
# print((6 + 3) * (6 + 3))
# print((6 + 3) / (6 + 3))
# print((6 + 3) // (6 + 3))
# print((6 + 3) ** (6 + 3))
# print((6 + 3) % (6 + 3))

# LIST IN PYTHON
#
# fruits = ["apple", "Banana", "Cherry", "Orange"]
# print(fruits)
#
# fruits = ["apple", "Banana", "Cherry", "Orange"]
# print(len(fruits))
#
# fruits = ["Apple", "Banana", "Cherry", "Orange"]
# fruits.append("Mango")
# print(fruits)
#
# fruits = ["Apple", "Banana", "Cherry", "Orange"]
# fruits.reverse()
# print(fruits)
#
# fruits = ["Apple", "Banana", "Cherry", "Orange"]
# fruits.remove("Orange")
# print(fruits)
#
# fruits = ["Apple", "Banana", "Cherry", "Orange"]
# fruits.clear()
# print(fruits)
#
# fruits = ["Apple", "Banana", "Cherry", "Orange"]
# del fruits
#
# fruits = ["Apple", "Banana", "Cherry", "Orange"]
# fruits.pop(2)
# print(fruits)
#
# fruits = ["Apple", "Banana", "Cherry", "Orange"]
# for x in fruits:
#     print(x)
#
# fruits = ["Apple", "Banana", "Cherry", "Orange", "Mango"]
# for x in fruits:
#     print(x)
#
# fruits = ["Apple", "Banana", "Cherry", "Orange"]
# for i in range(len(fruits)):
#     print(fruits[i])


# TUPLES IN PYTHON

# fruits = ("Apple", "Banana", "Orange", "Kiwi")
# print(fruits
#       )
#
# fruits = ("Apple", "Banana", "Orange", "Kiwi")
# print(len(fruits))
#
# fruits = ("Apple", "Banana", "Orange", "Kiwi")
# print(fruits[2:5])

fruits = ("Apple", "Banana", "Orange", "Kiwi")
print(fruits[-41:-1])

fruits = ("Apple", "Banana", "Cherry")
print(fruits[-3])

x = ("Apple", "Banana", "Cherry")
y = list(x)
y[2] = "cherry"
x = tuple(y)
print(x)







