# Rastgele Sayı Tahmin Oyunu - README

Bu Python programı, kullanıcıya 1 ile 5 arasında rastgele bir sayı tahmin etme şansı tanır. Programda kullanıcıya sadece üç kez tahmin yapma hakkı verilir. Doğru tahmin yaparsa, kullanıcı kazanır ve oyun sona erer. Yanlış tahmin yapılması durumunda ise üç deneme hakkı da tükenince "Başarısız oldunuz!" mesajı görüntülenir.

## Özellikler

- Kullanıcıya 1 ile 5 arasında rastgele bir sayı tahmin etmesi istenir.
- Kullanıcıya üç kez tahmin yapma hakkı tanınır.
- Doğru tahmin yapıldığında "Kazandınız!" mesajı verilir ve oyun sonlanır.
- Üç deneme sonunda yanlış tahmin yapılırsa, "Başarısız oldunuz!" mesajı görüntülenir.

## Kullanım

1. Python yüklü bir ortamda bu dosyayı çalıştırın.
2. Program, kullanıcıdan bir sayı tahmin etmesini isteyecektir.
3. Kullanıcı, tahminini girdikten sonra program sonucu kontrol eder.
4. Program üç denemeden sonra sona erer ve kullanıcıyı bilgilendirir.

## Örnek Çıktı

```
Enter your guess: 3
Enter your guess: 4
Enter your guess: 2
Sorry, you failed!
```

Veya doğru tahmin:

```
Enter your guess: 4
You won!
```

## Kullanıcı Geri Bildirimi

Eğer kullanıcı doğru tahmin yaparsa oyun hemen sona erer. Yanlış tahminler yapılması durumunda, üç hakkın sonunda kullanıcıya başarısız olduğu bildirilir.
