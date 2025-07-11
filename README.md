# artistik-stil-transferi
Görsel işleme teknikleriyle artistik stil transferi uygulaması.
# Artistik Stil Transferi (Python & OpenCV)

Bu proje, farklı artistik stil transferi tekniklerini Python ve OpenCV kullanarak uygular.  
Colab ortamında geliştirilmiştir.

## Özellikler
- Stil ve içerik görselleri yüklenerek farklı yöntemlerle stil transferi uygulanabilir.
- Kenar çıkarma (Canny, Sobel, Laplacian), histogram eşleştirme, Gabor ve FFT tabanlı stil transferi
- SSIM ve histogram benzerliği gibi metriklerle değerlendirme

## Kullanılan Kütüphaneler
- opencv-python
- numpy
- matplotlib
- scikit-image
- pillow

## Kurulum
1. Python 3.x kurulu olmalı.
2. Gerekli paketleri yüklemek için:
   ```
   pip install -r requirements.txt
   ```

## Kullanım
1. `imageprocessing_artistikstiltransferi.py` dosyasını çalıştır:
   ```
   python imageprocessing_artistikstiltransferi.py
   ```
2. Terminal/Colab yönlendirmelerini takip ederek stil ve içerik görsellerini yükle.
3. Sonuç görselleri ve metrikler ekranda görüntülenir.

## Örnek Sonuçlar

**İçerik Görseli**  
![content](results/content.png)

**Stil Görseli**  
![style](results/style.png)

**Çıktı (Stil Transferi Sonucu)**  
![result](results/result.png)

_(Not: Kendi örnek görsellerini “results” klasörüne ekleyip burada gösterebilirsin.)_

## Lisans
MIT

---

Geliştirici: [Emin Ogultarhan](https://github.com/KULLANICIADIN)
