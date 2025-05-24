**Giriş**  </br>
Dataset, kredi tahmini üzerine hazırlanmış olup 14 farklı sütundan ve 40.000 veri noktasından oluşmaktadır.
Proje kapsamına dataset ile KNN algoritması kullanılarak müşterilerin kredi almaya uygun olup olmadığı incelenmiştir. 
Keşifsel Veri Analizi(EDA), Görselleştirme, KNN algoritması, hiperparametre optimizasyonu yapılmıştır.
Hedef kolon olan "yes" ve "no" verileri "1" ve "0" olarak güncellenmiş ve modelin tahmin yapması sağlanmmıştır.
**KNN algoritması seçilmiştir çünkü; doğrusal olmayan bir sınıflandırma problemi karşısında daha iyi sonuçlar elde edilebileceğini düşündüm. Aynı zamanda hiperparametre optimizasyonu ile modelin performansı arttırmayı hedefledim.**

Proje kapsamına ML kütüphaneleri (pandas,matplotlib, seaborn.. ) aktif olarak tercih eilmiştir. Precision, recall, f1_score gibi sonuçlarda proje içerisinde yer almaktadır. Çıkan sonuçlara bağlı olarak Confusion Matrix incelenmiştir.

**Metrikler**

Öncelikle KNN algoritması oluğu için precision, recall ve f1 score değer elde edilmiştir.

**Class 0 (kredi verilmeyenler) için:**

Precision: 0.93 –  Kredi verilmesi uygun olmayan kişilerin tahimininde modelin %93lük bir başarı sağladığını görüyoruz.

Recall: 1.00 –  Kredi almaya uygun olmayan kişilerin tamamı doğru şekilde tahmin edilmiş.

F1-score: 0.96 – Bu sınıf için model başarılı.

**Sınıf 1 (kredi verilenler) için:**

Precision: 0.55 – Modelin krei verilmesi ugundur dediği kısmın %55 uygun.

Recall: 0.06 –  Kredi alabilecek kişilerin yalnızca %6’sı doğru tahmin edilmiş.

F1-score: 0.11 – Bu sınıf için ise modelin başarısı düşük.

**Ekler**

Proje de ek olarak  bir çalışma sergilenmemiştir. İsterlere uygun bir içerik üretmek hedeflenmiştir.

**Sonuç ve Gelecek Çalışmalar**

**Veri :** Öncelikle dataset oldukça dengesiz bir datasetti. Datasetin düzenlenmesi, yeni veri noktaları ekleyerek güzelleştirilmesi hedef halindedir.
**UI :**  Çalışma için kullanıcı dostu bir arayüz oluşturulabilir. Böylece kullanıcılar gerçek zamanlı kredi değerlendirmesi yapabilir.
**Algoritma :** Farklı algoritmalar üzerinde de çalışma tekrarlanabilir.

**Linkler**

https://www.kaggle.com/code/mihrayildiz/load-predictor </br>
https://www.kaggle.com/datasets/mihrayildiz/loan-pedictor-dtset





