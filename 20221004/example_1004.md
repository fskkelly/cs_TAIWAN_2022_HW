# input . print . type
```
x = input('Enter your name:')
print('Hello, ' + x)

a = input("請輸入：")
a

# 使用Python內建的type()函數顯示資料型態
type(a)
```
---
```
a = input("請輸入：")
a

b=a+1
b

# TypeError :資料型態(data type)錯誤
```

```
# 如何讀取使用者輸入的整數===>使用eval()函數 或int()
a = eval(input("請輸入："))
a

b=a+1
b
```
---
```
# space without ","
x, y, z = [int(x) for x in input("Enter three value: ").split()] 
print("First Number is: ", x) 
print("Second Number is: ", y) 
print("Third Number is: ", z) 
print()

# "," without space
x, y, z = [int(x) for x in input("Enter three value: ").split(",")] 
print("First Number is: ", x) 
print("Second Number is: ", y) 
print("Third Number is: ", z) 
print()

a, b = input("Enter a two value: ").split() 
print("First number is {} and second number is {}".format(a, b)) 
print()
```

# String modulo operator(%)
```
# 列印整數(integer)與 浮點數(float) 的值
print("Happy : %2d, Python : %5.2f" % (1, 05.333))
```

```
# 列印整數值 ==> %3d 和 %2d有 何不同
print("Total students : %3d, Boys : %2d" % (240, 120))
```

```
# print octal value
print("%7.3o" % (25))
```

```
# print exponential value
print("%10.3E" % (356.08977))
```

# Data types
- [Python Data Types](https://www.w3schools.com/python/python_datatypes.asp)

# Python Operators
- [Python Operators](https://www.w3schools.com/python/python_operators.asp)

# Python Escape Characters
- [Python Escape Characters](https://www.w3schools.com/python/python_strings_escape.asp)

# Python Strings
- [Python Strings](https://www.w3schools.com/python/python_strings.asp)
```
# 01234(5)
b = "Hello, World!"
print(b[2:5])
```

```
b = "Hello, World!"
print(b[:5])
```

```
b = "Hello, World!"
print(b[2:])
```

```
# Negative Indexing
b = "Hello, World!"
print(b[-5:-2])
```

```
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)

# or three single quotes '''xxxxxxx'''
```

```
a = " Hello, World! "
print(a.strip()) # returns "Hello, World!"
```

```
a = "Hello"
b = "World"
c = a + " " + b
print(c)
```

```
age = 36
txt = "My name is John, and I am {}"
print(txt.format(age))
```

# Python Lists
- [Python Lists](https://www.w3schools.com/python/python_lists.asp)
```
list1 = ["abc", 34, True, 40, "male"]
print(list1)
```

```
thislist = list(("apple", "banana", "cherry")) # note the double round-brackets
print(thislist)
```

```
thislist = ["apple", "banana", "cherry"]
thislist[1:2] = ["blackcurrant", "watermelon"]
print(thislist)
```

```
thislist = ["apple", "banana", "cherry"]
thislist[1:3] = ["watermelon"]
print(thislist)
```

```
thislist = ["apple", "banana", "cherry"]
thislist.insert(1, "orange")
print(thislist)
```

```
thislist = ["apple", "banana", "cherry"]
for i in range(len(thislist)):
  print(thislist[i])
```

```
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = []

for x in fruits:
  if "a" in x:
    newlist.append(x)
    
# newlist = [x for x in fruits if "a" in x]

print(newlist)
```

# Python Dictionaries
- [Python Dictionaries](https://www.w3schools.com/python/python_dictionaries.asp)
```
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)
```

```
# Duplicates Not Allowed
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964,
  "year": 2020
}
print(thisdict)
```

```
car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}

x = car.keys()

print(x) #before the change

car["color"] = "white"

print(x) #after the change
```

```
thisdict =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
for x, y in thisdict.items():
  print(x, y)
```

```
# Nested Dictionaries
child1 = {
  "name" : "Emil",
  "year" : 2004
}
child2 = {
  "name" : "Tobias",
  "year" : 2007
}
child3 = {
  "name" : "Linus",
  "year" : 2011
}

myfamily = {
  "child1" : child1,
  "child2" : child2,
  "child3" : child3
}
```
