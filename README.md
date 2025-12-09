# 🌍 Türkçemizin Coğrafyası: Edebi Kişiler ve Yöresel Ürünler Haritası

Bu proje, Denizli Adalet Ortaokulu bünyesinde, Türk Dili ve Edebiyatı ile coğrafi kültürümüzü dijital ortamda birleştirmek amacıyla geliştirilmiş interaktif bir web uygulamasıdır. Öğrencilerin ve meraklıların şehirlerimizi, şairlerimizi, yazarlarımızı ve yöresel lezzetlerimizi keşfetmelerini sağlar.

![Proje Görünümü](https://img.shields.io/badge/Durum-Canlı-success) ![Lisans](https://img.shields.io/badge/Lisans-MIT-blue)

## 🎯 Projenin Amacı

Öğrencilerimize ve kültür meraklılarına:
*   Şehirlerimizin yetiştirdiği önemli **edebi şahsiyetleri** tanıtmak,
*   Yöresel **coğrafi işaretli ürünleri** ve lezzetleri öğretmek,
*   Teknoloji ile kültürü harmanlayarak eğlenceli bir **öğrenme deneyimi** sunmak.

## ✨ Özellikler

*   **İnteraktif Türkiye Haritası:** Leaflet.js kütüphanesi kullanılarak hazırlanan, yakınlaştırılabilir (zoom) ve sürüklenebilir harita.
*   **Şehir Detayları:** Şehirlere tıklandığında açılan modern ve şık pencerede (modal) o şehre ait bilgiler.
*   **Dinamik İlçe Gösterimi (Özel):** Denizli iline yaklaşıldığında (zoom yapıldığında) **Tavas, Çal, Bozkurt, Çardak, Honaz, Babadağ, Sarayköy** gibi ilçelerin otomatik olarak belirmesi.
*   **Responsive Tasarım:** Hem masaüstü hem de mobil cihazlarda (telefon/tablet) sorunsuz çalışan duyarlı arayüz.
*   **Estetik Arayüz:** "Glassmorphism" (buzlu cam) efekti, özel yazı tipleri ve animasyonlarla zenginleştirilmiş modern tasarım.

## 🛠️ Kullanılan Teknolojiler

Bu proje tamamen açık kaynaklı teknolojilerle geliştirilmiştir:

*   **HTML5:** Sayfanın iskeleti ve semantik yapısı için.
*   **CSS3:** Özelleştirilmiş stiller, animasyonlar, Flexbox/Grid yapısı ve Glassmorphism efektleri için.
*   **JavaScript (ES6+):** Harita etkileşimleri, veri yönetimi ve dinamik DOM manipülasyonu için.
*   **[Leaflet.js](https://leafletjs.com/):** Açık kaynaklı, mobil dostu interaktif harita kütüphanesi.
*   **Google Fonts:** Okunabilirlik için 'Inter' ve estetik başlıklar için 'Playfair Display' fontları.

## 🚀 Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak için:

1.  Bu depoyu klonlayın:
    ```bash
    git clone https://github.com/ismihankuran/kultur_haritasi.git
    ```
2.  Klasörün içine girin:
    ```bash
    cd kultur_haritasi
    ```
3.  `index.html` dosyasını herhangi bir internet tarayıcısında (Chrome, Firefox, Edge vb.) açın.

Herhangi bir sunucu kurulumu gerektirmez, doğrudan çalışır.

## 📂 Proje Yapısı

```
turkiye_literature_map/
├── index.html      # Ana HTML dosyası (Yapı)
├── style.css       # Stil dosyası (Tasarım ve Görünüm)
├── script.js       # JavaScript dosyası (Harita Ayarları ve Veriler)
└── README.md       # Proje dokümantasyonu
```

## 📝 İçerik ve Veriler

Projede şimdilik aşağıdaki iller ve detayları bulunmaktadır (Liste zamanla güncellenecektir):
*   **İstanbul, Ankara, İzmir**
*   **Denizli** (ve ilçeleri: Tavas, Çal, Çardak, Bozkurt, Honaz, Babadağ, Sarayköy)
*   **Aydın** (ve Buharkent ilçesi)
*   **Trabzon, Erzurum, Diyarbakır**
*   **Gaziantep, Konya, Bursa**
*   **Adana, Mardin, Sivas**
*   **Eskişehir, Kahramanmaraş, Antalya**
*   **Çanakkale, Muğla, Manisa**
*   **Kütahya, Afyonkarahisar, Uşak**

## 👩‍🏫 Hazırlayan

**İsmihan KURAN**
*Türkçe Öğretmeni*
*Adalet Ortaokulu • Merkezefendi / DENİZLİ*

---
*Bu proje eğitim amaçlı hazırlanmıştır.*