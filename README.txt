MUSKİ SCADA — V2 (Mobil + Masaüstü)

DURUM: Çalışan prototip, canlı SCADA/PLC bağlantısı içermez.

Tüm cihazlarda ortak uygulama:
- Windows/Mac bilgisayarda Chrome / Edge / Safari
- iPhone: Safari (Ana Ekrana Ekle)
- Android: Chrome (Ana ekrana ekle / Uygulamayı yükle)

YAYINLAMA:
1. Bu klasördeki DOSYALARIN TÜMÜNÜ (index.html, app.js, styles.css,
   manifest.webmanifest, service-worker.js, icon dosyaları) bir GitHub Pages
   deposunun kök dizinine yükleyin.
2. GitHub Settings > Pages > Deploy from branch, main/(root) seçin.
3. Açılan HTTPS adresi hem iPhone hem Android hem bilgisayarda çalışır.
4. İlk çevrimiçi açılışta uygulama kabuğu önbelleğe alınır; sonrasında
   internet olmasa bile (tarayıcı önbelleği silinmedikçe) açılabilir.
5. iPhone'da Safari Paylaş > Ana Ekrana Ekle;
   Android'de Chrome ⋮ > Ana ekrana ekle/Uygulamayı yükle.

Yerel bilgisayarda kurulum gerekmez: index.html'i açmanız yeterlidir.
Telefonlarda ZIP/Dosyalar'dan HTML açmak tutarsız olduğundan HTTPS üzerinden
GitHub Pages yayını önerilir. GitHub Pages'de şema dosyaları sunucuya
otomatik yüklenmez; sadece indirilen yerel JSON dosyalarında saklanır.

MOBİL KULLANIM:
- Alt menü: Elemanlar, Çizim, Bilgiler, Envanter.
- Elemanlar'a girip örneğin Kuyu'ya dokunun; çizim ekranına eklenir.
- Elemanı tek parmakla taşıyın. Boş alanda tek parmakla kaydırın.
- İki parmakla yakınlaştırıp uzaklaştırın.
- 'Boru' veya 'Elektrik' aracını seçin ve iki elemana sırayla dokunun.
- Bilgiler ekranında seçilen elemanın özelliklerini değiştirin.
- Kaydet: .muski.json proje dosyası indirir; Aç: dosyayı yeniden okur.
- Dışa Aktar > PNG, SVG, yazdır/PDF. PDF seçeneğinin işleyişi tarayıcıya
  bağlıdır. Proje kaydını cihazın Dosyalar/İndirilenler alanında saklayın.

GÜVENLİK:
Gerçek altyapı bilgilerini internete yayınlanmış HTML/JavaScript içine
örnek veri olarak koymayın. Çizim JSON dosyalarını paylaşırken kurumun
veri güvenliği ve yetki kurallarına uyun.

V2: iPhone / Android uyarlaması, dokunmatik çizim ve mobil alt menü.
