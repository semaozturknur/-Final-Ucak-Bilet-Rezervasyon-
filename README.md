# -Final-Ucak-Bilet-Rezervasyon-
Bu proje, uçak bilet rezervasyonları için bir masaüstü uygulaması geliştirmeyi amaçlamaktadır. Kullanıcılar, uçak bilgilerini ekleyebilir, mevcut lokasyonları görüntüleyebilir ve uçuş rezervasyonları yapabilirler. Ayrıca, rezervasyon ekranında koltukların durumunu (satılmış/satılmamış) görebilir ve koltuk seçimi yapabilirler.

Proje İçeriği
Proje, aşağıdaki ana formlardan oluşmaktadır:

Uçak Formu: Uçak model, marka, seri numarası ve koltuk kapasitesi gibi bilgilerin listelendiği ve kaydedildiği form.
Lokasyon Formu: Ülke, şehir, havaalanı ve aktif/pasif durumlarının belirtildiği form.
Rezervasyon Formu: Koltukların satılma durumuna göre renk değiştirdiği ve koltuk üzerine tıklanarak müşteri bilgilerinin görüntülendiği form.
Kullanım
1. Uçak Ekleme
Uçak bilgilerini (Model, Marka, Seri No, Koltuk Kapasitesi) girin.
"Kaydet" butonuna tıklayarak bilgileri kaydedin.
2. Lokasyon Belirleme
Ülke, şehir ve havaalanı bilgilerini seçin.
Uçuş tarihini ve saatini girin.
"Kaydet" butonuna tıklayarak bilgileri kaydedin.
3. Rezervasyon Yapma
İlgili ülke, şehir ve havaalanını seçin.
Mevcut uçuşları listeleyin ve uçuşu seçin.
Koltukların durumunu (satılmış/satılmamış) görün.
Satılmamış koltuklara tıklayarak koltuk seçimi yapın.
"Onayla" butonuna tıklayarak seçiminizi onaylayın.
Özellikler
Uçak Formu:

Uçak model, marka, seri numarası ve koltuk kapasitesi ekleme.
Mevcut uçakları listeleme.
Lokasyon Formu:

Ülke, şehir ve havaalanı ekleme.
Mevcut lokasyonları listeleme.
Rezervasyon Formu:

Koltukların durumunu renklerle gösterme (satılmadıysa yeşil, satıldıysa kırmızı).
Koltuk seçimi ve müşteri bilgilerini görüntüleme.
Kod Yapısı
Models: Veritabanı modellerini içerir (Uçak, Lokasyon, Rezervasyon).
Data: Veritabanı bağlamı ve ilk başlatma işlemlerini içerir.
Forms: Kullanıcı arayüzü formlarını içerir.
Services: Veritabanı servislerini ve işlemlerini içerir.
Veritabanı
SQLite kullanılarak oluşturulan veritabanı, proje dizininde Data klasöründe bulunur. Veritabanı tabloları şu şekildedir:

Ucak: Uçak bilgilerini tutar.
Lokasyon: Lokasyon bilgilerini tutar.
Rezervasyon: Rezervasyon bilgilerini tutar.
