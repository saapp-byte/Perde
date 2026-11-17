# 🎭 Perde

**Ekranına başkası bakınca, ekranın sadece senin seçtiğin notu gösterir.**

Perde, telefonunun ön kamerasıyla ekrana kaç kişinin baktığını algılar. Yanındaki biri ekrana göz atınca üstte senin hazırladığın not veya görsel belirir, içerik gizlenir. Kişi bakmayı bırakınca her şey eski haline döner.

## ✨ Özellikler

- 👀 **Canlı yüz algılama:** Cihaz üzerinde çalışır, internet izni yoktur
- 📝 **Özel not veya görsel:** Perde devreye girince gösterilecek içeriği sen seçersin
- 🔢 **Ayarlanabilir tetikleme:** Kaç yüz görünce açılacağını belirlersin
- 📏 **Algılama mesafesi:** Uzaktaki yüzleri yakalama hassasiyeti ayarlanabilir
- 🔍 **Önizleme:** Perde'nin nasıl görüneceğini önceden test edebilirsin
- 🔔 **Arka planda çalışır:** Bildirimdeki "Durdur" tuşuyla istediğin an kapatabilirsin

## ⚙️ Nasıl çalışır?

1. Gösterilecek notu yaz veya bir görsel ekle.
2. Kaç yüz görünce açılacağını ve algılama mesafesini ayarla.
3. Perde'yi başlat, gerisini uygulama halleder.

## 🔒 Gizlilik

Tüm algılama telefonunda yapılır. Uygulama internete erişim izni istemez, hiçbir veri dışarı gönderilmez.

---

## 📲 İndir ve Test Et (Android)

1. [**Son sürümü indir**](https://github.com/saapp-byte/Perde/releases/latest) ve **`app-debug.apk`** dosyasına dokun.
2. İnen dosyayı aç ve yükle.
3. "Bilinmeyen kaynaklardan yükleme" veya Play Protect uyarısı çıkarsa **izin ver / Yine de yükle** de.

**Gereksinim:** Android 8.0 veya üzeri, ön kamera.

**İzinler:** Kamera (yüz algılama), diğer uygulamaların üzerinde gösterme (perde katmanı), bildirim.

## 🛠️ Sorun giderme

Uygulama arka planda kapanıyorsa (özellikle Xiaomi/MIUI):

- Pil tasarrufu: **Kısıtlama yok**
- Otomatik başlat: **Açık**
- Diğer izinler → Ekranın üzerinde göster: **Açık**
- Son uygulamalarda Perde kartını **kilitle**

## 🐞 Hata bildir

Bir hata bulursan [Issues](https://github.com/saapp-byte/Perde/issues) sayfasından bildir. Cihaz modelini ve Android sürümünü yazarsan sevinirim.

## 🔨 Kendin derle

```bash
git clone https://github.com/saapp-byte/Perde.git
cd Perde
gradle assembleDebug
```

APK şurada oluşur: `app/build/outputs/apk/debug/app-debug.apk`

---

⭐ Beğendiysen yıldız vermeyi unutma!
