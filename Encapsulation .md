# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length, width):
        # Private variables
        self.__length = length
        self.__width = width
    def print_inside(self):
        print(self.__length)
        print(self.__width)
    def get_length(self):
        return self.__length
    def get_width(self):
        return self.__width
rect = Rectangle(5, 3)
rect.print_inside()
```
## Output
<img width="979" height="865" alt="image" src="https://github.com/user-attachments/assets/5d4a5396-2464-4c05-a5b6-088261710011" />

## Result
Thus,the python program has been executed successfully.
