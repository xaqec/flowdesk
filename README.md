# Flowdesk AI — GitHub Pages

Bu klasördeki dosyaları GitHub deponuzun köküne yükleyin. `index.html` doğrudan depo kökünde olmalı. ZIP dosyasını önce açın; ZIP dosyasının kendisini yüklemeyin.

1. GitHub üzerinde yeni bir depo oluşturun.
2. Add file → Upload files ile `index.html`, `css/`, `js/` ve `.nojekyll` dosyasını yükleyip commit edin.
3. Settings → Pages → Build and deployment altında Source: Deploy from a branch seçin.
4. Branch: main, Folder: / (root) seçip Save düğmesine basın.
5. Yayın tamamlandığında Pages ekranında görünen site bağlantısını açın.

Derleme komutu, npm, Node.js veya sunucu gerekmez. Dosya yolları göreli olduğu için GitHub Pages proje adreslerinde çalışır. `.nojekyll` dosyası gizli olabilir; saf HTML/CSS/JS site bu dosya olmadan da çalışır.

Bu, kurgusal bir SaaS ürününün tanıtım sitesidir. Yapay zekâ, giriş ve kayıt ekranları etkileşimli demolardır; gerçek servis bağlantısı yoktur. İletişim formu mesaj göndermek yerine yerel bir metin dosyası indirir. Yazı tipleri internet bağlantısıyla Google Fonts üzerinden yüklenir; yüklenemezse sistem yazı tipi kullanılır.
