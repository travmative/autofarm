# Mnks's AutoFarm [BASIC]

Roblox için hafif, şık arayüzlü bir **konum kaydetme, ışınlanma ve otomatik farm** scripti. Kayıtlı noktalara tek tıkla ışınlanabilir, belirlediğin aralıkla otomatik teleport yapabilir, oyuncuları listeleyip yanlarına gidebilirsin.

>  • Discord: `findhost`

---

## Özellikler

### Points (Noktalar)
- Bulunduğun konumu isim vererek kaydet
- **TP**: Kayıtlı noktaya anında ışınlan
- **AUTO**: Seçili noktaya ayarlanan aralıkla sürekli ışınlan (otomatik farm)
- **Key**: Her noktaya klavye tuşu ata, tuşa basınca ışınlan
- **X**: Noktayı sil

### Players (Oyuncular)
- Sunucudaki oyuncuların listesi (görünen ad + kullanıcı adı)
- Canlı mesafe ve HP bilgisi
- Tek tıkla oyuncunun yanına ışınlanma

### Settings (Ayarlar)
- **Anti-AFK**: AFK atılmayı engeller
- **Background Blur**: Menü açıkken arka plan bulanıklığı
- **FPS & Ping HUD**: Sürüklenebilir, gökkuşağı renkli FPS/ping göstergesi
- **Auto-TP Delay**: Otomatik ışınlanma aralığı (0.1 – 60 sn)
- **Server Hop**: Başka bir halka açık sunucuya geçiş
- **FPS Boost**: Materyalleri, decal'leri ve partikülleri kapatan düşük grafik modu
- **17 tema**: DARK, OCEAN, SAKURA, EMBER, MIDNIGHT, CYBERPUNK, LIGHT, NEON, FOREST, BLOOD, ICE, GOLD, GRAPE, MINT, SUNSET, SKY, CHROMA

### Diğer
- Animasyonlu açılış ekranı
- Sürüklenebilir menü
- Bildirim sistemi
- Menü aç/kapat tuşu: **Insert** (`_G.MenuKey` ile değiştirilebilir)

---

## Kurulum

1. Roblox için uyumlu bir script executor kullan.
2. Scripti executor'a yapıştır veya dosyadan yükle.
3. Oyuna girdikten sonra çalıştır.

```lua
-- Repo'ya yükledikten sonra kendi linkinle değiştir
loadstring(game:HttpGet("https://raw.githubusercontent.com/KULLANICI_ADI/REPO_ADI/main/autofarm.lua"))()
```

---

## Kullanım

| İşlem | Nasıl |
|-------|-------|
| Menüyü aç/kapat | `Insert` |
| Konum kaydet | **POINTS** sekmesinde isim yaz → **ADD** |
| Işınlan | Noktanın yanındaki **TP** |
| Otomatik farm | Noktanın yanındaki **AUTO** (tekrar basınca durur) |
| Tuş ata | **Key: None** yazısına tıkla, sonra bir tuşa bas |
| Oyuncuya git | **PLAYERS** sekmesi → **TP** |
| Ayarlar | **SETTINGS** sekmesi |

### Yapılandırma

Script başında şu değişkenleri düzenleyebilirsin:

```lua
_G.MenuKey = "Insert"   -- Menü tuşu
_G.TpDelay = 1          -- Auto-TP aralığı (saniye)
_G.BlurEnabled = false  -- Arka plan bulanıklığı
_G.HudEnabled = true    -- FPS/Ping HUD
_G.AntiAFK = false      -- Anti-AFK
```

---

## Notlar

- Kayıtlı noktalar ve tuş atamaları kalıcı değildir; oyundan çıkınca sıfırlanır.
- Server Hop yalnızca boş yeri olan halka açık sunucuları bulur.
- Script `CoreGui` kullandığı için sadece executor ortamında çalışır.

## Sorumluluk Reddi

Bu proje yalnızca eğitim amaçlıdır. Üçüncü taraf scriptlerin kullanımı Roblox Hizmet Şartları'na aykırı olabilir ve hesabının kısıtlanmasına yol açabilir. Kullanım tamamen **kendi sorumluluğundadır**.

## Krediler

**Created by MNK's**
 • Discord: `findhost`
