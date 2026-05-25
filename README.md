# sarki-sozu-analizi
# Şarkı Sözleri Üzerinden Metin Madenciliği ve Benzerlik Analizi

Bu proje, veri bilimi ve doğal dil işleme (NLP) yöntemleri kullanılarak Türk müziğindeki ikonik sanatçıların şarkı sözlerini analiz etmek amacıyla geliştirilmiştir.

## 📊 Veri Seti İçeriği
Proje kapsamında 5 farklı sanatçının (Teoman, Sagopa Kajmer, Sezen Aksu, Şebnem Ferah, Müslüm Gürses) en popüler 10'ar şarkısı olmak üzere toplam **50 şarkıdan oluşan orijinal bir veri seti** Genius API aracılığıyla toplanmıştır. 

## 🛠️ Yapılan Analizler ve Yöntemler
* **Veri Ön İşleme:** Şarkı sözlerindeki temizleme, satır başı düzenlemeleri ve noktalama işaretleri ayıklanmıştır.
* **Metin Temsili:** Kelimelerin anlamsal ilişkilerini yakalamak adına metin madenciliği yöntemleri kullanılmıştır.
* **Benzerlik Analizi:** Şarkıların birbirine olan anlamsal yakınlıkları **Kosinüs Benzerliği (Cosine Similarity)** algoritması ve Word2Vec modelleri ile test edilmiş, r2 skorları ve benzerlik matrisleri çıkarılmıştır.
* **Görselleştirme:** Elde edilen benzerlik oranları Matplotlib ve Seaborn kütüphaneleriyle ısı haritası (heatmap) ve grafiklere dönüştürülmüştür.
