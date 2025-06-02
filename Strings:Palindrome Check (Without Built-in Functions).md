# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

      s = "google"
      rev = s[::-1]
      if s == rev:
          print("The string is a palindrome.")
      else:
          print("The string is not a palindrome.")
## Output
![image](https://github.com/user-attachments/assets/c5be19aa-9aeb-42c8-9765-004fd15672f1)

## Result
The Python program to check if the string "google" is a palindrome using slicing has been executed successfully, and the output has been verified.
