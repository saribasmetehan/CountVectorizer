# CountVectorizer ve Spam E-Mail Tespit Modeli

Bu repo, **CountVectorizer** kullanımı ile ilgili temel bilgileri ve **CountVectorizer** ile **Random Forest** kullanarak oluşturulmuş basit bir spam e-mail tespit modelini içermektedir.

## CountVectorizer Nedir?

CountVectorizer, doğal dil işleme (NLP) görevlerinde bir metin belgeleri koleksiyonunu sayısal bir gösterime dönüştürmek için yaygın olarak kullanılan bir metin ön işleme tekniğidir. Python'da popüler bir makine öğrenimi kütüphanesi olan **scikit-learn**'ün bir parçasıdır.

Bu araç, metin verilerini analiz edebilmek için onları kelime sıklıklarına göre temsil eden bir vektör formatına dönüştürür. Her bir kelimenin belge içinde kaç kez geçtiğini hesaplayarak kelimelerden oluşan bir "özellik matrisi" oluşturur.

## Repo İçeriği

1. **Temel CountVectorizer Kullanımı:** 
   - CountVectorizer'ın temel işleyişi ve parametreleri hakkında örnekler.
   - Metinlerin nasıl sayısal veriye dönüştürüldüğüne dair örnek kodlar.
   - CountVectorizer'ın bazı parametrelerinin kullanımı.

2. **Spam E-Mail Tespit Modeli:**
   - Hugginface'den dataset yüklenmesi ve veri ön işleme adımları.
   - Spam ve ham e-maillerden oluşan örnek veri seti üzerinde CountVectorizer ve Random Forest algoritması kullanarak model oluşturulması.
   - Modelin score değerlerinin gösterimi.
   - E-mail içeriklerinin spam olup olmadığını tespit etmek için modelin kullanımı.
