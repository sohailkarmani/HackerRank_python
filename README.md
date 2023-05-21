# HackerRank_python
# Solution 01
if __name__ == '__main__':
    print("Hello, World!")
    
    
# Solution 02

import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(input().strip())

if n % 2 != 0:
    print("Weird")
elif n % 2 == 0 and 2 <= n <= 5:
    print("Not Weird")
elif n % 2 == 0 and 6 <= n <= 20:
    print("Weird")
elif n % 2 == 0 and n > 20:
    print("Not Weird")
    
    
   
# Solution 03
if __name__ == '__main__':
    a = int(input())
    b = int(input())
    
    print(a+b)
    print(a-b)
    print(a*b)
    
    
   
    
   # Solution 04
   
   if __name__ == '__main__':
    a = int(input())
    b = int(input())
    print(a//b)
    print(a/b)
    
    
   # Solution 05
   if __name__ == '__main__':
    n = int(input())


for i in range(n):
    print(i ** 2)
    
    
   # Solution
   
   def is_leap(year):
   # leap = False
    
    # Write your logic here
    if year%4==0:
        if year%100==0:
            if year%400==0:
                leap=True
            else:
                leap=False
        else:
             leap=True
    else:
        leap=False

    return leap




year = int(input())
print(is_leap(year))
    
