# simple-calculator.py
my first self code

program



print("simple calculator")
a = int(input("enter the number:"))
op = input("enter the operator(+,*,-,/,//,**):")
b = int(input("enter the number:"))
if op=='+':
     print("answer:",a+b)
elif op=='-':
     print("answer:",a-b)
elif op=='*':
     print("answer:",a*b)
elif op=='/':
     if b==0:
         print("canot divided by zero")
     else:
         print("answer:",a/b)
elif op=='//':
    print("answer:",a//b)
elif op=='**':
    print("answer:",a**b)

