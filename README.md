# 1 задание
# "строки"
a = "один"
b = "два"
print(a)
print(b)
# "числа"
a = 12
b = 23
print(a)
print(b)

f = int(input("Введите число:"))
print(f)

name = str(input('Введи своё имя: '))
print(name)
# 2 задание
a = int(input("Введите время в секундах:"))
h=(a//3600)
m=(a//60)%60
s=a%60
if h<10:
    h='0'+str(h)
else:
    h=str(h)
if m<10:
    m='0'+str(m)
else:
    m=str(m)
if s<10:
    s='0'+str(s)
else:
    s=str(s)
print(h+':'+m+':'+s)


# 3 задание
n = int(input('Введите число'))
t = str(n)
t1 = t + t
t2 = t + t + t
comp = n + int(t1) + int(t2)
print (comp)

# 4 задание
i = int(input('Введите число'))
r = -1
while i > 0:
    d = i % 10
    i //= 10
    if d > r:
        r = d
print(r)
# 5 задание
vr = int(input('Введите выручку:'))
iz = int(input('Введите издержки:'))
if vr > iz:
    print('прибыль — выручка больше издержек')
    pr = vr - iz
    rv = pr/vr
    print('Рентабельность выручки - ',rv)
else:
    print('убыток — издержки больше выручки')
sf = int(input('Введите кол-во сотрудников'))
print('прибыль фирмы в расчете на одного сотрудника:',pr/sf)
# 6 задание
a = int(input())
b = int(input())
i = 1
while a < b:
    a *= 1.1
    i += 1
print(i)
