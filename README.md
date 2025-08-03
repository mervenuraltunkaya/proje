# 🛡️ Tüketici Hakları AI Asistanı

Modern AI teknolojisi ile tüketici haklarınızı öğrenin, sorularınıza anında cevap alın ve haklarınızı güvenle koruyun.

## ✨ Özellikler

- 🤖 **AI Destekli Danışman** - Gemini AI ile akıllı tüketici hakları rehberliği
- 🌓 **Dark/Light Mode** - Göz dostu tema seçenekleri
- 📱 **Responsive Tasarım** - Tüm cihazlarda mükemmel deneyim
- 🔒 **Güvenli API Yönetimi** - Environment variables ile güvenli anahtar saklama
- ⚡ **Hızlı Erişim** - Sık sorulan sorular için tek tık çözümler

## 🚀 Kurulum

### 1. Projeyi İndirin
```bash
git clone https://github.com/your-username/tuketici-haklari-ai.git
cd tuketici-haklari-ai
```

### 2. API Anahtarını Ayarlayın

#### Yöntem A: Environment Variables (Önerilen)
1. `.env` dosyasını oluşturun:
```bash
cp .env.example .env
```

2. `.env` dosyasını düzenleyin:
```env
VITE_GEMINI_API_KEY=your_actual_api_key_here
```

#### Yöntem B: Runtime'da Giriş
API anahtarını ayarlamazsanız, uygulama ilk kullanımda sizden isteyecektir.

### 3. Çalıştırın
Basit HTTP sunucusu ile:
```bash
# Python 3
python -m http.server 8000

# Node.js (http-server gerekli)
npx http-server

# PHP
php -S localhost:8000
```

Tarayıcıda `http://localhost:8000` adresine gidin.

## 🔑 API Anahtarı Alma

1. [Google AI Studio](https://aistudio.google.com/) adresine gidin
2. Google hesabınızla giriş yapın
3. **"Get API Key"** butonuna tıklayın
4. **"Create API Key"** seçeneğini seçin
5. Anahtarı kopyalayın ve `.env` dosyasına yapıştırın

## 📁 Proje Yapısı

```
tuketici-haklari-ai/
├── index.html          # Ana HTML dosyası
├── styles.css          # CSS stilleri
├── script.js           # JavaScript fonksiyonları
├── .env                # Environment variables (GİT'e yüklenmez)
├── .gitignore          # Git ignore kuralları
└── README.md           # Proje dokümantasyonu
```

## 🎯 Kullanım

### Ana Özellikler
- **Kategori Rehberleri**: İade, garanti, kargo, şikayet süreçleri
- **AI Chat**: Günlük dilde soru sorma ve detaylı cevaplar alma
- **Hızlı Erişim**: Popüler sorular için tek tık çözümler
- **Tema Değiştirme**: Sağ üstteki 🌙/☀️ butonu

### Örnek Sorular
- "Aldığım telefon bozuk, ne yapabilirim?"
- "Kargo geç geldi, paramı geri alabilir miyim?"
- "14 günlük iade sürem geçti, ne olacak?"
- "Mağaza garantiyi kabul etmiyor, nereye başvurabilirim?"

## 🛡️ Güvenlik

- API anahtarları `.env` dosyasında saklanır
- `.gitignore` ile hassas dosyalar Git'e yüklenmez
- Environment variables ile production güvenliği
- LocalStorage ile tarayıcı bazlı güvenli saklama

## 🔧 Geliştirme

### Yerel Geliştirme
```bash
# Canlı yeniden yükleme için
npx live-server
```

### API Entegrasyonu Test
```javascript
// Konsolta test edin
getAIResponse("test sorusu").then(console.log);
```

## 📦 Deployment

### GitHub Pages
1. Repository'yi GitHub'a yükleyin
2. Settings → Pages → Source: Deploy from a branch
3. Branch: main seçin
4. API anahtarını GitHub Secrets'e ekleyin

### Netlify
1. Netlify'e proje klasörünü sürükleyin
2. Environment variables kısmına API anahtarınızı ekleyin
3. Deploy butonuna tıklayın

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Commit yapın (`git commit -m 'feat: add amazing feature'`)
4. Push yapın (`git push origin feature/amazing-feature`)
5. Pull Request açın

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakın.

## 🆘 Destek

- 🐛 **Bug raporu**: GitHub Issues kullanın
- 💡 **Özellik isteği**: GitHub Issues'da etiketleyin
- 📧 **İletişim**: [your-email@example.com]

## 🔗 Bağlantılar

- [Google AI Studio](https://aistudio.google.com/)
- [Gemini API Docs](https://ai.google.dev/docs)
- [Tüketici Hakları](https://www.tuketici.gov.tr/)

---

⭐ **Projeyi beğendiyseniz yıldız vermeyi unutmayın!**