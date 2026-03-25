## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithmhttps://github.com/sakthipriyagajendran/Module-2/edit/main/Loops-Palindrome%20Number%20check.md
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
n=int(input())
temp=n
reverse=0
while temp>0:
    digit=temp%10
    reverse=reverse*10+digit
    temp//=10
if n==reverse:
    print("The given number",n,"is a Palindrome")
else:
    print("The given number",n,"is not a palindrome")
## Output
<img width="976" height="257" alt="image" src="https://github.com/user-attachments/assets/e03ac177-2fb2-4c80-81d0-d3b539c2dc68" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
