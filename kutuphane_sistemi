kitap_isimleri=["Savaş ve Barış", "1984","Bülbülü Öldürmek","Kırmızı Pazartesi"]
kitap_durumlari=["Müsait","Ödünçte","Müsait","Müsait"]

while True:
    print("Menü:")
    print("1. Kitap ismini kullanıcıdan alma")
    print("2. Kitap ismini görüntülemek")
    print("3. Kitap ödünç alma")
    print("4. Kitap iade etme")
    print("5. Çıkış")
    secim=int(input("Lütfen bir seçim yapınız"))

    if secim==1:
        kitap=input("Eklenecek kitap adını giriniz")
        kitap_isimleri.append(kitap)
        kitap_durumlari.append("Müsait")
        print(f"{kitap} adlı kitap listeye eklendi")
    elif secim==2:
        for i in range(len(kitap_isimleri)):
            print(f"{kitap_isimleri[i]}: {kitap_durumlari[i]}")
    elif secim==3:
        kitap_ismi=input("Ödünç almak istediğiniz kitap ismini giriniz")
        if kitap_ismi in kitap_isimleri:
            index=kitap_isimleri.index(kitap_ismi)
            if kitap_durumlari[i]=="Müsait":
               kitap_durumlari[i]=="Ödünçte"
               print(f"{kitap_ismi} kitabı ödünç alındı")
            else:
                print(f"{kitap_ismi} kitap iadede değil")
                
            
        
            
               
    elif secim==4:
        kitap_ismi=input("İade etmek istediğiniz kitap ismini giriniz")
        if kitap_ismi in kitap_isimleri:
            index=kitap_isimleri.index(kitap_ismi)
            if kitap_durumlari[i]=="Ödünçte":
               kitap_durumlari[i]=="Müsait"
               print(f"{kitap_ismi} kitabı iade edildi")
            else:
                print(f"{kitap_ismi} kitap ödünçte değil")
           
               
    elif secim==5:
        print("Çıkış yapılıyor")
        break
               
    
    
