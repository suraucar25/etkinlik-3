# etkinlik-3
#Şirket Ödeme Politikası:
hesap=int(input("hesabınız kaç TL tuttu?"))
bahşiş=int(input("Kaç TL bahşiş vermek istersiniz?"))
tutar=(int(hesap+bahşiş))
müştutar=int(input("kaç TL ödediniz"))
if tutar == müştutar:
    print("teşekkürler")
elif tutar > müştutar:
    print("eksik ödeme yapıldı")
elif tutar < müştutar:
    para=(int(müştutar - tutar))
    if para >= 200:
     adet = para // 200
     print("200 TL :", adet)
     para = para % 200

    if para >= 100:
     adet = para // 100
     print("100 TL :", adet)
     para = para % 100

    if para >= 50:
     adet = para // 50
     print("50 TL :", adet)
     para = para % 50

    if para >= 20:
     adet = para // 20
     print("20 TL :", adet)
     para = para % 20

    if para >= 10:
     adet = para // 10
     print("10 TL :", adet)
     para = para % 10

    if para >= 5:
     adet = para // 5
     print("5 TL :", adet)
     para = para % 5

    if para >= 1:
     adet = para // 1
     print("1 TL :", adet)
     para = para % 1
