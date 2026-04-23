# LinkedIn Sidebar Cleaner

LinkedIn'in sağ kenar çubuğundaki dikkat dağıtıcı widget'ları bağımsız olarak gizleyen Tampermonkey/Violentmonkey scripti.

---

## Özellikler

- 10 farklı widget türü bağımsız olarak açılıp kapatılabilir
- Tüm gizleme tek tıkla devre dışı bırakılabilir
- Ayarlar kaydedilir, sayfa yenilenince hatırlanır
- LinkedIn'in tüm sayfalarında çalışır

---

## Gizlenebilen Widget'lar

| Widget | Açıklama |
|---|---|
| **Tanıyor Olabilirsiniz** | "People you may know" bağlantı önerileri |
| **LinkedIn Learning** | Kurs ve öğrenme önerileri |
| **Trend Haberler** | LinkedIn Haberleri ve gündem konuları |
| **Reklamlar** | Sponsorlu ve reklam kutuları |
| **Premium Satış Kutuları** | "LinkedIn Premium'a yükselt" gibi kutular |
| **Etkinlikler** | Önerilen etkinlikler widget'ı |
| **Sayfaları Takip Et** | Önerilen şirket ve sayfa takip kutusu |
| **Gruplar** | Grup önerileri widget'ı |
| **İş Önerileri Kutusu** | "Daha fazla iş keşfet" widgetları |
| **Hashtag Önerileri** | Takip edilebilecek hashtagler |

---

## Kurulum

1. Tarayıcına [Tampermonkey](https://www.tampermonkey.net/) ya da [Violentmonkey](https://violentmonkey.github.io/) eklentisini yükle.
2. [linkedin-sidebar-cleaner.user.js](./linkedin-sidebar-cleaner.user.js) dosyasını aç.
3. Eklentinin kontrol panelinde **Yeni Script Ekle**'ye tıkla, içeriği yapıştır ve kaydet.
4. LinkedIn'i yenile.

**Uyumluluk:** Chrome · Edge · Firefox

---

## Kullanım

Sol üst köşede küçük bir panel belirir.

- **Kenar Çubuğu** butonu (mavi = açık) tüm gizlemeyi tek seferde açar/kapatır
- **⚙ Yönet** butonu hangi widget'ların gizleneceğini seçtiğin paneli açar
- Paneldeki her satırın sağındaki toggle o widget'ı bağımsız olarak kontrol eder
- **Tümünü Gizle / Tümünü Göster** butonları toplu işlem yapar
- Sol üstteki sayı kaç widget'ın o an gizlendiğini gösterir

---


## Lisans

MIT
