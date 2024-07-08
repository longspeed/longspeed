#bai 1:
i = int(input("Choose a number: "))
while i < 10:
    i = int(input("Choose a number: "))
#bai 2:
import random
i = random.randint(1,10)
a = int(input("Choose a random number from 1 to 10: "))
while a != i:
    a = int(input("Choose a random number from 1 to 10: "))
print("You guessed the right number")
#bai 3:
import random
a = input("Người chơi 1: ")
b = input("Người chơi 2: ")
f = 1
print("Lượt 1: ")
c = input("Người chơi 1 ra: ")
d = input("Người chơi 2 ra: ")
while c == "búa" and d == 'bao' or c == 'bao' and d == "kéo" or c == "kéo" and d == "búa" or c =="kéo" and d == "kéo" or c == "búa" and d == "búa" or c=="bao" and d == "bao":
    f = f+1
    print("Lượt" ,f )
    c = input("Người chơi 1 ra: ")
    d = input("Người chơi 2 ra: ")
print("Người chơi 1 đã thắng trong",f,"Lượt")
#bai 4:
import time
a = int(input("Nhập thời gian đếm ngược : "))

while a != 0:
    print(a)
    time.sleep(1)
    a = a - 1
