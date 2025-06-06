## Proje Açıklaması

Bu projede, görsellerden otomatik olarak açıklama (caption) üretmek için BLIP (Bootstrapped Language-Image Pretraining) modelinin özelleştirilmesini hedeflenmiştir. Kullanılan modelin adı Salesforce/blip-image-captioning-base. 22 bin resim ve açıklamadan oluşan veri setiyle model fine-tune edilerek eğitilmiştir.
3 epoch ile eğitilen modelin Bleu skoru %27 olarak ölçülmüştür. Bu oran genel olarak bakıldığında iyi model anlamlı ve doğru cümleler kurabiliyor, modelin görmediği görsellerlede test edildi ve iyi sonuçlar verdi.

Son olarak da bu model flask api ile Web uygulamasına entegre edildi.

## Uygulama Görseli

![Ekran görüntüsü 2025-06-06 175445](https://github.com/user-attachments/assets/e3f695d4-5365-4d15-8297-267919410d5e)
