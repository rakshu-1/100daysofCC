## Given a month - an integer from 1 to 12, print the number of days in it in the year 2017.

```

Example input #1
1
(January)

Example output #1
31

Example input #2
2
(February)

Example output #2
28

```
# Read an integer:
a = int(input())
# Print a value:
# print(a)

if(a==2):
  print("28")
elif(a==4 or a==6 or a==9 or a==11 ):
  print("30")
else:
  print("31")
