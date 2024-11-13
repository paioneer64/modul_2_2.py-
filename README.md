print("введите три числа ")
first = int(input("первое "))
second = int(input("второе "))
third = int(input("третье "))
if first==second and first == third and second == third:
    print(3)
elif first == second and second != third or first == third and second != third:
    print(2)
else:
    print(0)
