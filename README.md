# Code-The-Matrix
Problem solution code.
This is an update.

## Task 0.5.25
base = 10
digets = set(range(11))|{11,99,999}
print('digets = ',digets,'\nBase = ',base)
dict3 = {x:[(x%base**3)//base**2,(x%base**2)//base,x%base] for x in digets}
print(dict3)


digets =  {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 99, 999} 
Base =  10
{0: [0, 0, 0], 1: [0, 0, 1], 2: [0, 0, 2], 3: [0, 0, 3], 4: [0, 0, 4], 5: [0, 0, 5], 6: [0, 0, 6], 7: [0, 0, 7], 8: [0, 0, 8], 9: [0, 0, 9], 10: [0, 1, 0], 11: [0, 1, 1], 99: [0, 9, 9], 999: [9, 9, 9]}

