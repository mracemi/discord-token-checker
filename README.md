# Discord Token Checker

Discord Token Checker, Discord kullanıcı token'larını doğrulamak ve kullanıcı bilgilerini görüntülemek için geliştirilmiş bir Electron uygulamasıdır. Uygulama, kullanıcıların tekil veya çoklu token'ları kontrol edebilmesini sağlar ve iki dilde (Türkçe ve İngilizce) kullanılabilir.

## Özellikler

- **Tekil Token Kontrolü**: Kullanıcılar doğrudan bir Discord token'ı girebilir ve geçerliliğini kontrol edebilir
- **Çoklu Token Kontrolü**: .txt dosyası aracılığıyla birden fazla token'ı toplu olarak kontrol etme
- **Detaylı Kullanıcı Bilgileri**: Token geçerliyse kullanıcı adı, ID, avatar, e-posta, telefon numarası, doğrulanma durumu, hesap oluşturma tarihi ve Nitro durumu gibi bilgileri gösterir
- **İki Dilli Arayüz**: Türkçe ve İngilizce dilleri arasında geçiş imkanı
- **Sayfalandırma**: Sonuçları sayfa sayfa görüntüleme
- **Modern Tasarım**: Koyu temalı, kullanıcı dostu arayüz

## Gereksinimler

- Node.js (v14 veya üzeri)
- npm (Node Package Manager)

## Kurulum

1. Bu projeyi bilgisayarınıza klonlayın veya ZIP olarak indirin
2. Proje dizinine gidin:
   ```bash
   cd discord-token-checker
   ```
3. Gerekli bağımlılıkları yükleyin:
   ```bash
   npm install
   ```

## Kullanım

Uygulamayı başlatmak için aşağıdaki komutu kullanın:

```bash
npm start
```

Alternatif olarak, doğrudan Electron ile başlatmak için:

```bash
npx electron .
```

## Nasıl Kullanılır

1. Uygulamayı başlattığınızda, tek bir token girmek veya bir dosya yüklemek için iki seçenek göreceksiniz
2. **Tek Token**: Discord token'ınızı metin alanına yapıştırın ve "Tek Token'ı Kontrol Et" butonuna tıklayın
3. **Çoklu Token**: Token'larınızı her satıra bir tane olacak şekilde içeren bir .txt dosyası seçin ve "Dosyadaki Token'ları Kontrol Et" butonuna tıklayın
4. Sonuçlar kartlar halinde görüntülenecek ve sayfalandırma ile yönetilecektir
5. Uygulama dilini değiştirmek için sayfa üst kısmındaki dil seçiciyi kullanabilirsiniz

## Güvenlik Uyarısı

Bu uygulama sadece kendi token'larınızı kontrol etmek için tasarlanmıştır. Başkalarının token'larını kontrol etmek veya yetkisiz erişim sağlamak için kullanmayın. Discord'un hizmet şartlarını ihlal etmek hesabınızın askıya alınmasına neden olabilir.

## Katkıda Bulunma

Katkıda bulunmak isterseniz, lütfen bir issue oluşturun veya bir pull request gönderin.

## Lisans

Bu proje MIT Lisansı ile lisanslanmıştır - detaylar için [LICENSE](LICENSE) dosyasına bakın.