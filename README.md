Hacker-Rank-Challenge-Solutions
===============================

UtopianTree

z = input()
for i in range (z):
    x = input()
    a = x
    y = 1
    while a > 0:
        y = y * 2
        a -= 1
        if a <= 0:
            break
        y = y + 1
        a -= 1
    print y    
