# patterns-numeric-2-
n=int(input())
for i in range(n):
  for j in range(n):
    if i>=j:
      print(f"{i+1}",end=" ")
    else:
      print(" ",end=" ")
  print()
