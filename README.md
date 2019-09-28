# find-out-upper-and-lower-case-of-a-string

name = input('enter the name: ')

for i in range(len(name)):
    ch = name[i]
    chcode = ord(ch)
    if chcode >= 97 and chcode <= 122:
        print(f'{ch} is lower')
    else:
        print(f'{ch} is upper')
