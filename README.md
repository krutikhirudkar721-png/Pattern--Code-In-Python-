# Pattern--Code-In-Python-
# Right-Angled Triangle Pattern(Right Half Pyramid)
# 1. using two for loop

for i in range(1,6):
  for j in range(0,i):
    print("*",end=" ")
  print()

# 2. Using single for loop

for i in range(1,6):
  print(" *"*i)
  
# Right-Angled Triangle Pattern(Left Half Pyramid)
# 1.

n = 5
for i in range(1, n + 1):
    print(" " * (n - i) + "*" * i)
    
# 2.

for i in range(1, 6):
    print(" " * (5 - i) + "*" * i)
