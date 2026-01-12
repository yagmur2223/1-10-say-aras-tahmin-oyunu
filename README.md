# 1-10-say-aras-tahmin-oyunu
import random
tutulan_sayi=random.randint(1,10)
while True:
    tahmin=int(input("tahmininizi giriniz="))
    if tahmin<tutulan_sayi:
        print("daha büyük bir sayı dene")
    elif tahmin>tutulan_sayi:
        print("daha küçük bir sayı dene")
    else:
        print("tebrikler bukdunuz")
        break
