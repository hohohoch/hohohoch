- 👋 Hi, I’m @hohohoch
- I am newbie on python and faced with the problem of incorrect operation of the code.
- Can you help me please with this cod.
- Here is the code, if anything , he 's on python.
- import random
a = 'камень'
b = 'ножницы'
c = 'бумага'

print('выбери')
print(a,'(1)')
print(b,'(2)')
print(c,'(3)')
ver = 0
while (ver == 0):
        player = int(input(" "))
        if (player == 1 or player == 2 or player == 3):
            ver = 1
if player == 1:
        print("Вы выбрали камень.")
if player == 2:
        print("Вы выбрали ножницы.")
if player == 3:
        print("Вы выбрали бумагу.")
spisok = ['paper','scissors','stone']

print(random.choice(spisok))
if spisok[0] and player == 1:
    win = 1
if spisok[0] and player == 2:
    win = 0
if spisok[0] and player == 3:
    win = 3
if spisok[1] and player == 1:
    win = 0
if spisok[1] and player == 2:
    win = 3
if spisok[1] and player == 3:
    win = 1
if spisok[2] and player == 3:
    win = 0
if spisok[2] and player == 2:
    win = 1
if spisok[2] and player == 1:
    win = 3

if win == 0:
        print("Draw!")
if win == 1:
        print("win player!")
if win == 2:
        print("win PC!")
