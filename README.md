Proje Raporu: Çizge Renklendirme ile Ders Programı Hazırlama
1. Giriş
Bu proje, üniversite dersleri için renkli bir program oluşturmak için graf renklendirme algoritmalarını kullanarak otomatik bir sistem oluşturmayı amaçlamaktadır. Sağlanan PHP kodu, kullanıcılara farklı öğretmenler için oluşturulan programı görüntüleme ve güncelleme olanağı sağlar.

2. Hedefler
Üniversite dersleri için bir program oluşturmanın sürecini otomatikleştirmek.
Çakışmaları önlemek için bir graf renklendirme algoritması uygulamak.
Programı görüntüleme ve güncelleme için kullanıcı dostu bir arayüz sunmak.
3. Metodoloji
Proje, sunucu taraflı betikleme için PHP ve bilgileri öğretmenler, dersler ve programlar hakkında depolamak için MySQL veritabanını kullanır.
Daha iyi kod organizasyonu ve bakımı için nesne tabanlı programlama prensiplerini kullanır.
Sistem, dersleri çakışma olmaksızın programlamak için bir graf renklendirme algoritması uygulayarak bir program oluşturur.
4. Uygulama Detayları
Veritabanı Bağlantısı: Proje, veritabanına bağlanmak için (connection.php) bir bağlantı kurar ve öğretmenler, dersler ve programlar hakkında bilgi almak için bu veritabanından yararlanır.

Veri Alımı: Öğretmenler ve ilgili dersleri veritabanından hazırlanan ifadeler kullanılarak alınır.

Program Oluşturma: Sistem, bir graf renklendirme algoritması kullanarak derslere renk atayarak bir program oluşturur. Bu sırada öğretmenlerin tercihleri ve ders programları dikkate alınır.

Kullanıcı Arayüzü: Proje, HTML ve Bootstrap kullanarak kullanıcı arayüzü sağlar. Öğretmen adları sekme olarak görüntülenir ve bunların ilgili programları gösterilir.

Güncelleme Fonksiyonelliği: Öğretmenler, sağlanan arayüz aracılığıyla (update_ders.php) ders programlarını güncelleyebilir. Değişiklikler veritabanına kaydedilir.

5. Sonuçlar
Sistem, farklı öğretmenler için renkli programlar başarıyla oluşturur.
Kullanıcılar öğretmen sekmesi aracılığıyla kolayca gezinebilir ve ilgili ders programlarını görebilir.
6. Tartışma
Ders programlamak için kullanılan graf renklendirme algoritması, çakışma olmadan dersleri programa yerleştirmeyi sağlar.
Kullanıcı arayüzü sezgisel ve kullanıcı dostudur, bu da öğretmenlerin programlarını güncellemede kolaylık sağlar.
7. Sonuç
Proje, üniversite ders programlarının otomatik oluşturulmasında etkili bir çözüm sunar. Graf renklendirme algoritmalarının kullanımı, derslerin çakışma olmadan programa yerleştirilmesini sağlar ve kullanıcı arayüzü genel kullanıcı deneyimini artırır.
