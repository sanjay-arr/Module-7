# # 🔁 Recursion:Sum of Digits using Recursion in Python
NAME : G SANJAY
---
REG NO : 212224230243
---
## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:
  def sum_digits(num):
      if num < 0 or int(num) != num:
          return 0
      elif num == 0:
          return 0
      else:
          return (num % 10) + sum_digits(num//10)
  num= int(input())
  print(sum_digits(num))

## OUTPUT
![image](https://github.com/user-attachments/assets/02d60b88-a02f-4083-aa2d-3e1787ae10ca)

## RESULT
Thus, the program has been executed successfully.
