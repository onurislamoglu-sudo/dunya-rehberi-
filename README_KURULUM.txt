
OTOMATIK APK KURULUMU - 3 ADIMDA TELEFONUNA KUR

ADIM 1: GitHub'a Yükle
1. github.com'da yeni repo oluştur (ismi dunya-rehberi yap)
2. Bu klasördeki TÜM dosyaları o repoya yükle (Upload files)

ADIM 2: APK Otomatik Derlensin
1. Repo'da üstte Actions sekmesine tıkla
2. APK Build workflow'u çalışacak (1-2 dakika)
3. Bittiğinde yeşil tik olacak

ADIM 3: APK'yı İndir ve Kur
1. Actions > En son build'e tıkla
2. Aşağıda Artifacts bölümünde dunya-rehberi-apk.zip var
3. İndir, içinden app-debug.apk çıkıyor
4. Telefonuna at ve kur

Bu yöntemle Android Studio kurmana bile gerek yok!

ALTERNATIF: Android Studio varsa
Build > Build APK(s) de, app/build/outputs/apk/debug/app-debug.apk hazır.
