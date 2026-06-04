# testt

## Dosyalar
- ar-viewer.html     → AR görüntüleyici
- Ekran görüntüsü 2026-06-02 140814.png  → Marker görseli
- 3SHAFA.gltf   → 3D model

## ÖNEMLI: .mind Dosyası
MindAR.js, marker görselinizi bir .mind binary dosyasına dönüştürmenizi gerektirir.
Bu adımı ÜCRETSIZ online araçla yap:

  https://hiukim.github.io/mind-ar-js-doc/tools/compile

1. Yukarıdaki siteye git
2. Marker görselini (Ekran görüntüsü 2026-06-02 140814.png) yükle
3. "Compile" butonuna bas
4. İndirilen "targets.mind" dosyasını "Ekran görüntüsü 2026-06-02 140814.mind" olarak yeniden adlandır
5. Bu .mind dosyasını da aynı klasöre koy

## Deploy (HTTPS Zorunlu)

### Netlify (En Kolay - Ücretsiz)
1. app.netlify.com adresine git
2. "Deploy manually" seç
3. Tüm dosyaları (ar-viewer.html + marker + model + .mind) sürükle-bırak
4. Sana bir URL verir: https://xxxx.netlify.app

### GitHub Pages (Ücretsiz)
1. Yeni GitHub repo oluştur
2. Tüm dosyaları yükle
3. Settings > Pages > main > Save
4. URL: https://KULLANICIADI.github.io/REPO/ar-viewer.html

## QR Kodu Oluştur
Deploy URL'ini şu siteye gir: https://qr.io veya https://qrcode.com

## Kullanım
1. QR kodu telefon kameranla tara
2. Chrome (Android) veya Safari (iOS) otomatik açılır — UYGULAMA GEREKMİYOR
3. Kamera izni ver
4. Kamerayı "Ekran görüntüsü 2026-06-02 140814.png" görseline doğrult
5. 3D model belirir!
