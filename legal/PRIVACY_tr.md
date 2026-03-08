# 🔒 Gizlilik Politikası — Rezonans

**Son Güncelleme:** 8 Mart 2026  
**Yürürlük Tarihi:** 4 Mart 2026

---

## 1. Giriş

Rezonans ("biz", "uygulama") olarak gizliliğinize saygı duyuyor ve kişisel verilerinizin korunmasını en önemli önceliklerimizden biri olarak görüyoruz.

Bu Gizlilik Politikası; Rezonans mobil uygulamasını kullanırken hangi kişisel verilerin toplandığını, bu verilerin nasıl kullanıldığını, kimlerle paylaşıldığını ve haklarınızı açıklamaktadır.

Uygulamayı kullanarak bu politikayı kabul etmiş sayılırsınız. Kabul etmiyorsanız lütfen uygulamayı kullanmayın.

---

## 2. Veri Sorumlusu

**Ad/Unvan:** Furkan Pala  
**E-posta:** furkanpala404@gmail.com  
**Uygulama Adı:** Rezonans  

---

## 3. Topladığımız Veriler

### 3.1 Hesap ve Kimlik Bilgileri
Kayıt sırasında aşağıdaki veriler toplanır:

- **E-posta adresi** (email/şifre ile kayıt)
- **Ad ve soyad** (profil oluşturma)
- **Doğum tarihi** (yaş doğrulama)
- **Cinsiyet** (eşleştirme algoritması)
- OAuth ile girişte; **Google Hesabı** veya **Apple ID** kimlik bilgileriniz (yalnızca doğrulama amaçlı, şifreniz alınmaz)

### 3.2 Profil Bilgileri
Profilinizi oluştururken isteğe bağlı olarak sağladığınız:

- Profil fotoğrafları
- **Ses profili kaydı** (5 saniyelik tanıtım)
- Biyografi / hakkımda metni
- Müzik türü ve ilgi alanı tercihleri
- Meslek, eğitim bilgisi (isteğe bağlı)

### 3.3 Konum Verisi
- Uygulamayı kullandığınız sırada **yaklaşık konum** (şehir/ilçe düzeyi) alınır
- Tam GPS koordinatları depolanmaz
- Konum paylaşımını uygulama ayarlarından devre dışı bırakabilirsiniz

### 3.4 Kullanım ve Etkileşim Verileri
- Beğeni, süper beğeni, geçme işlemleri
- Görüntülenen profiller
- Mesajlaşma geçmişi (şifreli olarak saklanır)
- Uygulama içi satın alım geçmişi (abonelik durumu)

### 3.5 Cihaz ve Teknik Veriler
- Cihaz modeli ve işletim sistemi versiyonu
- Uygulama versiyonu
- Push bildirim token'ı (FCM)
- Kilitlenme raporları ve hata logları (anonim)

---

## 4. Verilerin Kullanım Amaçları

Topladığımız verileri yalnızca aşağıdaki amaçlarla kullanırız:

| Amaç | Kullanılan Veri |
|---|---|
| Hesap oluşturma ve doğrulama | E-posta, ad, doğum tarihi |
| Profil gösterimi ve eşleştirme | Fotoğraf, ses, tercihler, konum |
| Gerçek zamanlı sohbet | Mesaj içeriği |
| Push bildirimleri gönderme | FCM token |
| Premium abonelik yönetimi | Satın alım geçmişi |
| Uygulama güvenliği ve doğrulama | Cihaz bilgisi, kullanım logu |
| Kullanıcı desteği | E-posta, hesap bilgisi |
| Yasal yükümlülükler | Gerekli minimum veri |

---

## 5. Veri Paylaşımı

### Paylaşmadığımız Şeyler
- Kişisel verilerinizi **üçüncü taraflara satmayız.**
- Reklam ağlarıyla profil bilgisi **paylaşmayız.**

### Kullandığımız Üçüncü Taraf Hizmetler

| Hizmet | Amaç | Gizlilik Politikası |
|---|---|---|
| **Supabase** | Veritabanı ve depolama | [supabase.com/privacy](https://supabase.com/privacy) |
| **Firebase (Google)** | Bildirimler, analitik | [policies.google.com](https://policies.google.com/privacy) |
| **RevenueCat** | Abonelik yönetimi | [revenuecat.com/privacy](https://www.revenuecat.com/privacy/) |
| **Google Sign-In** | OAuth girişi | [policies.google.com](https://policies.google.com/privacy) |
| **Apple Sign-In** | OAuth girişi | [apple.com/privacy](https://www.apple.com/privacy/) |

Bu hizmetler yalnızca belirtilen amaçlar doğrultusunda veri işler ve kendi gizlilik politikalarına tabidir.

---

## 6. Veri Güvenliği

Verilerinizi korumak için aşağıdaki teknik önlemleri alıyoruz:

- ✅ Tüm veri iletimi **SSL/TLS** şifreleme ile korunur
- ✅ Şifreler hiçbir zaman düz metin olarak saklanmaz (bcrypt)
- ✅ Mesajlar **uçtan uca şifreli** olarak iletilir
- ✅ Ses kayıtları güvenli depolama alanında saklanır
- ✅ Veritabanı erişimi rol bazlı yetkilendirme ile kontrol edilir
- ✅ Düzenli güvenlik güncellemeleri uygulanır

Hiçbir sistem %100 güvenli değildir. Bir güvenlik açığı fark ederseniz lütfen **furkanpala404@gmail.com** adresine bildirin.

---

## 7. Veri Saklama Süreleri

| Veri Türü | Saklama Süresi |
|---|---|
| Aktif hesap verileri | Hesap silinene kadar |
| Mesaj geçmişi | Hesap silinene kadar veya kullanıcı tarafından silinene kadar |
| Ses profili | Güncelleme/silme yapılana kadar |
| Kilitlenme logları (anonim) | 90 gün |
| Silinen hesap verileri | Silme talebinden itibaren 30 gün (yedek temizliği) |

---

## 8. Çocukların Gizliliği

Rezonans **18 yaş ve üzerindeki** bireyler için tasarlanmıştır.

- Bilerek 18 yaş altı kullanıcıdan veri toplamıyoruz.
- Bir çocuğa ait veri topladığımızı fark edersek bu verileri derhal sileriz.
- Ebeveynler veya veliler endişelerini **furkanpala404@gmail.com** adresine iletebilir.

---

## 9. Haklarınız (KVKK Kapsamında)

6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) uyarınca aşağıdaki haklara sahipsiniz:

| Hak | Açıklama |
|---|---|
| **Bilgi alma** | Kişisel verilerinizin işlenip işlenmediğini öğrenme |
| **Erişim** | İşlenen verilerinize erişim talep etme |
| **Düzeltme** | Yanlış veya eksik verilerin düzeltilmesini isteme |
| **Silme** | Verilerinizin silinmesini talep etme ("unutulma hakkı") |
| **İtiraz** | Belirli işleme faaliyetlerine itiraz etme |
| **Taşınabilirlik** | Verilerinizi yapılandırılmış formatta alma |
| **İşlemeyi kısıtlama** | Belirli koşullarda veri işlemeyi durdurma |

**Başvuru için:** furkanpala404@gmail.com adresine yazmanız yeterlidir. Talepler **30 gün** içinde yanıtlanır. Kimlik doğrulama amacıyla ek bilgi istenebilir.

---

## 10. Çerezler ve Takip

Rezonans mobil uygulaması tarayıcı çerezi kullanmaz. Ancak uygulama performansını ölçmek amacıyla **Firebase Analytics** aracılığıyla anonim kullanım istatistikleri toplanabilir.

Analitik veri toplamayı cihaz ayarlarınızdan veya uygulama ayarlarından devre dışı bırakabilirsiniz.

---

## 11. Uluslararası Veri Transferleri

Bazı üçüncü taraf hizmetlerimiz (Supabase, Firebase, RevenueCat) verilerinizi Türkiye dışındaki sunucularda işleyebilir. Bu transferler, yeterli veri koruma standartlarına sahip ülkelere veya standart sözleşme hükümleri kapsamında gerçekleştirilir.

---

## 12. Hesap ve Veri Silme

Hesabınızı ve tüm verilerinizi silmek için:

1. Uygulamada **Profil → Ayarlar → Hesabı Sil** yolunu izleyin, **veya**
2. **furkanpala404@gmail.com** adresine "Hesap Silme Talebi" konusuyla e-posta gönderin

Silme işlemi sonrası verileriniz **30 gün** içinde tüm sistemlerimizden kalıcı olarak kaldırılır. Yasal yükümlülükler gereği saklanması gereken veriler bu süreçten muaf tutulabilir.

---

## 13. Bu Politikadaki Değişiklikler

Bu gizlilik politikasını zaman zaman güncelleyebiliriz. Önemli değişiklikler olduğunda:

- Uygulama içi bildirim göndeririz
- Bu sayfanın üstündeki **"Son Güncelleme"** tarihini güncelleriz

Politikayı düzenli olarak incelemenizi öneririz. Uygulamayı kullanmaya devam etmeniz güncel politikayı kabul ettiğiniz anlamına gelir.

---

## 14. İletişim

Bu gizlilik politikasıyla ilgili sorularınız veya talepleriniz için:

📧 **E-posta:** furkanpala404@gmail.com  
⏱️ **Yanıt süresi:** Genellikle 24–48 saat içinde

---

<p align="center">
  © 2025–2026 Rezonans. Tüm hakları saklıdır.
</p>
