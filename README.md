# Drawing-a-rhombus-with-a-different-small-diameter
x = int(input())
t = x
print("*"*(x+2))
n = 1
while t>0 :
  print("*"*int(((t+1)/2))+" "*(n)+"*"*int(((t+1)/2)))
  t = t-2
  n = n + 2
w = t+4
m = x - 2
while w < x+2:
  print("*"*int(((w+1)/2))+" "*(m)+"*"*int(((w+1)/2)))
  w = w+2
  m = m - 2
print("*"*(x+2))
