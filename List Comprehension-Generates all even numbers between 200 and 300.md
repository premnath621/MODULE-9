# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

## 💻 PROGRAM:
Add Code Here
class Generate:
    def __init__(self, first,d,last):
        self.first = first
        self.d = d
        self.last=last
    def Ap_generate(self):
        L=[i for i in range(self.first,self.last+1,self.d)]
        return L
Series = Generate(200,2,301)
print(Series.Ap_generate())
## OUTPUT:
<img width="1225" height="174" alt="image" src="https://github.com/user-attachments/assets/967c7e19-b050-4bac-8baf-2d2c6cafe025" />

## RESULT:
Thus the output is verified.
