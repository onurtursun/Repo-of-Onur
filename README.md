# PYTON PROBLEM SETLERİ
This repo created by Onur Tursun

#Pyton Problem Seti 1

#fizzbuzz

f = int(input("Baslangic sayisini seciniz: "))
b = int(input("Bitis sayisini giriniz: "))
for a in range(f,b):
    if a % 15 == 0:
        print("FizzBuzz")
    elif a % 3 == 0 :
        print("Fizz")
    elif a % 5 == 0:
        print("Buzz")
    else:
        print(a)


#Pyton Problem Seti 2

#Pyton Problem Seti 3

#en büyük tek sayıyı bulma
sayılar = []
a = input("Liste için arada sadece boşluklar kullanarak ardışık sayılar giriniz:")
while len(sayılar) == 10:
    sayılar.append(a)
sayılar.append(a)
m = int(max(a))
if m % 2 == 1:
    print(m)
else :
    print(m-1)


#Pyton Problem Seti 4

#Pyton Problem Seti 5

#hayalimdeki sınıf
class hayalimdekisınıf():
    dizaynı = []
    sıralar = []
    tahta = []
    öğrenciler = []
Csınıfı = hayalimdekisınıf()
Csınıfı.dizaynı = "çift kapılı geniş sınflar tavanı yüksek öğrenciler için rahat"
Csınıfı.sıralar = "geniş bireysel sıralar aynı zamanda çanta askılığı var"
Csınıfı.tahta = "Büyük bir kara tahta yanında akıllı tahta "
Csınıfı.öğrenciler = "C sınıfının daimi öğrencileri"
def F():
    aga = [Csınıfı.dizaynı,Csınıfı.öğrenciler,Csınıfı.sıralar,Csınıfı.tahta]
    print(aga)
