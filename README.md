# OkulYokla — APK Build

## GitHub Actions ile APK Derleme

### 1. Bu repoyu GitHub'a yükle

```bash
git init
git add .
git commit -m "İlk commit"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADINIZ/okulyokla.git
git push -u origin main
```

### 2. APK otomatik derlenir

- Push yapınca GitHub Actions otomatik başlar
- **Actions** sekmesinden ilerlemeyi izleyebilirsiniz (~5-10 dakika)

### 3. APK'yı indir

- Actions → En son workflow → **OkulYokla-APK** artifact'ını indir
- `app-debug.apk` dosyasını telefona yükle

### 4. Telefona yükleme

- Android ayarlardan **"Bilinmeyen kaynaklardan yükleme"** izni ver
- APK dosyasını aç ve yükle

## Notlar

- Bu debug APK'dır, kişisel kullanım için uygundur
- Play Store için release APK ve keystore gereklidir
