# Alzheimer Dostu Kelime Avı Oluşturucu

Bu proje, yapay zeka kullanılarak Alzheimer hastaları için özel olarak tasarlanmış, zihni yormayan, nostaljik ve pozitif kelimeler içeren, tamamen saf (Vanilla) HTML/CSS/JS ile yazılmış bir bulmaca ve PDF oluşturma aracıdır.

## Öne Çıkan Özellikler

- **Tampon Bölge Algoritması:** Kelimelerin birbirine temas etmesini ve harf paylaşmasını engelleyen özel yerleşim motoru.
- **Yaşlı Dostu Tasarım:** Zorluk seviyesine göre dinamik olarak büyüyen/küçülen okunaklı ızgara hücreleri.
- **Nostaljik Kelime Havuzu:** Günlük hayattan, pozitif anıları tetikleyen (Aile, Soba, Radyo, Bayram vb.) 3-11 harf arası özenle seçilmiş Türkçe kelimeler.
- **Akıllı Otomatik Doldurma:** Eksik kalan kelime slotlarını havuzdan tekrar etmeden tek tuşla rastgele doldurma.
- **A4 Uyumlu Çift Sayfa PDF Çıktısı:**
  - 1. Sayfa: Bulmaca tablosu ve aranacak kelimeler listesi.
  - 2. Sayfa: Çözüm anahtarı (renklendirilmiş doğru konumlar).

## Teknik Yapı

- **Ön Yüz:** HTML5, CSS3 (Modern Flexbox, CSS Grid mantığı)
- **Mantık:** Saf JavaScript (Vanilla JS)
- **PDF Dışa Aktarma:** `html2pdf.js` kütüphanesi

## Kullanım

1. `index.html` dosyasını indirin veya klonlayın.
2. Dosyayı herhangi bir modern web tarayıcısında açın.
3. Zorluk seviyesini seçin.
4. Kendi kelimelerinizi girin veya "Eksik Yerleri Rastgele Doldur" butonunu kullanın.
5. "Bulmacayı Oluştur ve PDF İndir" butonuna basarak çıktı alın.

## GitHub Pages ile Yayınlama

Projeyi GitHub deposuna yükledikten sonra `Settings > Pages` sekmesinden `main` dalını (branch) seçerek saniyeler içinde canlıya alabilirsiniz.
