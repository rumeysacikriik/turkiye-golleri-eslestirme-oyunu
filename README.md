# turkiye_golleri_eslestirme_oyunu

Türkiye'deki coğrafi göllerin konumlarını interaktif bir harita üzerinde sürükle-bırak (Drag and Drop) mekanizmalarıyla öğretmeyi amaçlayan, frontend tabanlı dinamik bir oyunlaştırma (gamification) projesidir.

## Projenin Amacı ve Konusu
Bu proje; web teknolojilerinin eğitim ve oyunlaştırma süreçlerindeki rolünü göstermek amacıyla geliştirilmiştir. Kullanıcılar, liste halindeki göl isimlerini Türkiye haritası üzerindeki doğru koordinat noktalarıyla eşleştirerek hem coğrafya bilgilerini test ederler hem de web üzerinde akıcı bir kullanıcı deneyimi yaşarlar.

---

## Teknik Altyapı & Fonksiyonel Özellikler
Proje tamamen istemci taraflı (client-side) modern web teknolojileri (HTML5, CSS3, Vanilla JavaScript) kullanılarak tek bir sayfa (Single Page) mimarisiyle geliştirilmiştir:

* **Gelişmiş Sürükle-Bırak Mekanizması:** JavaScript sürükleme olayları (`dragstart`, `dragover`, `drop`) optimize edilerek, göl etiketlerinin harita üzerindeki hedef dairesel alanlarla pürüzsüz ve senkronize bir şekilde eşleşmesi sağlanmıştır.
* **Dinamik Skor ve İstatistik Takibi:** Kullanıcının yaptığı her doğru ve yanlış hamle gerçek zamanlı olarak takip edilir, skor tablosu anlık güncellenir ve oyun sonunda kullanıcıya başarı raporu sunulur.
* **Hata ve Geri Bildirim Yönetimi:** Yanlış eşleştirmelerde hedef noktaların görsel olarak uyarılması (animasyonlu sarsıntı efekti) ve doğru eşleştirmelerde ilgili göle ait detaylı bilgilerin anlık olarak bilgi kutusunda (popup) gösterilmesi sağlanmıştır.

---

## Tasarım Yaklaşımı & UI/UX Kararları
* **Modern & Canlı Renk Paleti:** Kullanıcı etkileşimini ve enerjisini yüksek tutmak amacıyla arayüzde canlı renk geçişleri (Linear Gradient: pastel mavi, mor ve pembe tonları) tercih edilmiştir.
* **Kullanıcı Dostu Bilgi Akışı:** Ekran yerleşimi, kullanıcının sol taraftaki etiket havuzundan elemanları seçip sağ taraftaki harita alanına en az eforla sürükleyebileceği sezgisel bir hiyerarşide (Layout) tasarlanmıştır. Doğru yerleştirilen her eleman görsel bir rozete (pill) dönüşerek görsel bütünlüğü korur.
