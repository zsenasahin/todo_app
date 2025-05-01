# Flutter Todo App with Firebase

Bu Flutter uygulaması, Firebase Firestore kullanarak gerçek zamanlı bir Todo list uygulamasıdır. Kullanıcılar görevler ekleyebilir, düzenleyebilir ve silebilir, ayrıca görevlerin tamamlanma durumunu takip edebilirler.

## Özellikler

- ✨ Modern ve kullanıcı dostu arayüz
- 🔄 Gerçek zamanlı veri senkronizasyonu
- 📱 Responsive tasarım
- 🎨 Özelleştirilmiş ikonlar
- 📅 Tarih ve saat seçici
- ✅ Görev tamamlama durumu
- 🗑️ Görev silme özelliği

## Kullanılan Teknolojiler

- Flutter
- Firebase Firestore
- SVG İkonlar
- Custom Fonts (Cascadia Code)
- Material Design 3

## Paketler

```yaml
dependencies:
  flutter:
    sdk: flutter
  firebase_core: ^2.24.2
  cloud_firestore: ^4.13.6
  flutter_svg: ^2.0.10+1
  intl: ^0.19.0
  modal_bottom_sheet: ^3.0.0
```

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/your-username/todo_app.git
```

2. Bağımlılıkları yükleyin:
```bash
flutter pub get
```

3. Firebase projenizi oluşturun ve yapılandırın:
   - Firebase Console'dan yeni bir proje oluşturun
   - Flutter uygulamanızı Firebase'e ekleyin
   - `google-services.json` dosyasını `android/app` klasörüne ekleyin
   - Web için Firebase yapılandırmasını `index.html` dosyasına ekleyin

4. Uygulamayı çalıştırın:
```bash
flutter run
```

## Uygulama Özellikleri

### Todo Ekleme
- Sağ alt köşedeki + butonuna tıklayarak yeni todo ekleyebilirsiniz
- Her todo için:
  - İkon seçimi (10 farklı kategori)
  - Başlık
  - Açıklama
  - Tarih ve saat

### Todo Yönetimi
- Checkbox ile görevleri tamamlandı olarak işaretleme
- Tamamlanan görevlerin üzeri çizili gösterilir
- Görevleri silme özelliği
- Silme işlemi için onay dialog'u

### Arayüz Özellikleri
- Özel arka plan tasarımı
- Cascadia Code font kullanımı
- Material Design 3 uyumlu bileşenler
- Yuvarlatılmış köşeler ve gölgeler
- Kategoriye özel SVG ikonlar

## Katkıda Bulunma

1. Bu repository'yi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Bir Pull Request oluşturun
