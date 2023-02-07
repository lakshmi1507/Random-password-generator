# Random-password-generator
import random
import string
print("enter how many passwords you want to generate")
a=int (input())
print("length of password")
l=int(input())
def listtostring(s):
    str1=""
    for ele in s:
        str1+=ele
    return str1

    
for x in range(a):
    password=[]
    for i in range(l):
        alpha=random.choice(string.ascii_letters)
        password.append(alpha)
    s=password
    print(listtostring(s))
