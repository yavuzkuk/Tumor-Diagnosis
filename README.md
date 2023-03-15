## Tumor 

Drive üzerinde bulunan bu veri seti toplamda 3264 tane fotoğraf verisi içeriyor. Amacımız, eğittiğimiz bir modelde, rastgele bir görüntüde tümörün var olup olmadığını tespit etmek.

![tümör](https://user-images.githubusercontent.com/102716932/225234650-dfea5cdc-4879-44a1-ac94-04f3ffe82825.png)


Bu doğrultuda, kullanılan CNN mimarilerinin başarı oranları şu şekildedir:

- AlexNet: %74
- ResNet: %78
- DenseNet: %82
- LeNet: %77



![tümör2](https://user-images.githubusercontent.com/102716932/225234802-a2232d8a-cc14-4199-a28f-60718beb474e.png)


Uygulanılan adımlar:

- Drive üzerinde bulunulan dosyaların tek tek içine girip listeye eklendi.
- Aynı şekilde etiket bilgileri de ayrı bir dosyaya eklendi.
- Verilen dizinlere girerek verileri sırayla aldığı için önce veriler karıştırıldı, sonra veriler train ve test verileri olarak dörde bölündü.
- Sözel olan etiket verileri kategorik verilere çevirildi.
- Daha sonra dört farklı CNN mimarsi oluşturulup, elde ettiğimiz veriler üzerinden eğitildi ve test edildi.

!! Sonuçlar veri setinin durumuna ve modellerin parametrelerine göre değişkenlik gösterebilir.
