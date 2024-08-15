# Basic Informational Site

Bu proje, Node.js kullanarak statik HTML dosyalarını URL yollarına göre sunan basit bir bilgi sitesidir.

## Proje Dosyaları

- `index.html`: Ana sayfa
- `about.html`: Hakkında sayfası
- `contact-me.html`: İletişim sayfası
- `404.html`: 404 hata sayfası
- `index.js`: Node.js sunucu dosyası

## Başlangıç

1. **Proje dizinine gidin**:
   ```bash
   cd <proje-dizini>
    ```
2. **Sunucuyu başlatın**:
    ```bash
    node index.js
    ```
3. **Web sitesine erişin**:

- `Ana sayfa`: `http://localhost:8080`
- `Hakkında`: `http://localhost:8080/about`
- `İletişim`: `http://localhost:8080/contact-me`
- Bilinmeyen URL'ler 404 sayfasını gösterir.
