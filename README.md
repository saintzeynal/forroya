# Gəmi Oyunları

Gəmidə boş vaxtı keçirmək üçün beş oyun. **İnternet tələb olunmur**: heç bir şəkil, şrift, səs faylı və ya kitabxana yüklənmir. Bütün qrafika kodla çəkilir, səslər isə brauzerin özündə yaradılır.

## Necə açmaq olar

1. Qovluğu açın və **`index.html`** faylına iki dəfə klikləyin (və ya telefonda toxunun).
2. Açılan səhifədə oynamaq istədiyiniz oyunun kartına toxunun.
3. Hər oyunun yuxarısında **«Menyuya qayıt»** və **səs** düymələri var.

Hər hansı müasir brauzer (Chrome, Edge, Firefox, Safari) işləyir.

## Oyunlar

| Fayl | Oyun | Qısa izah |
|---|---|---|
| `oyun1-deniz-yolu.html` | Dəniz Yolu | Qayalardan qaç, konteynerləri topla, rekordunu yenilə. |
| `oyun2-praktikani-doy.html` | Praktikanı Döy | Stres əleyhinə oyun: silah seç, ox düyməsinə bas. «MÜALİCƏ ET» ilə qurbanı sağalt. |
| `oyun3-liman-bulmacasi.html` | Liman Bulmacası | Konteynerləri sarı-qara yerlərə it. 15 səviyyə. |
| `oyun4-deniz-doyusu.html` | Dəniz Döyüşü | Klassik gəmi batırma: donanmanı yerləşdir, kompüterə qarşı döyüş (3 səviyyə). |
| `oyun5-baliq-tutma.html` | Balıq Tutma | Sakit balıq ovu, 17 növ balıq, gün-gecə dövrü. |

## İdarəetmə

- **Telefon:** toxunma, barmağı sürüşdürmə və ekrandakı düymələr.
- **Kompüter:** siçan və klaviatura.
  - Dəniz Yolu: ← → və ya A D; fasilə üçün P.
  - Praktikanı Döy: ← ↑ → (zərbə), 1–7 (silah), H (müalicə).
  - Liman Bulmacası: ox düymələri / WASD, Z (geri al), R (yenidən).
  - Dəniz Döyüşü: toxun (hədəf seç), yenə toxun və ya ATƏŞ düyməsi; klaviaturada ox düymələri + Enter, R (gəmini döndər).
  - Balıq Tutma: Boşluq düyməsi (basılı saxla və burax), A (albom).

## Telefona və ya fleşkaya köçürmək

Bütün qovluğu **olduğu kimi** köçürmək lazımdır, çünki `index.html` digər fayllara keçid verir.

**Fleşka / kompüter:** qovluğu (`for roya`) fleşkaya kopyalayın. Başqa kompüterdə `index.html` faylını açın.

**Android telefon:**
1. Qovluğu USB kabellə və ya fleşka ilə telefonun yaddaşına köçürün (məsələn, `Download/gemi-oyunlari`).
2. Fayl menecerində `index.html` faylına toxunun və **Chrome** ilə açın.
   Fayl açılmasa, Chrome-un ünvan sətrinə `file:///storage/emulated/0/Download/gemi-oyunlari/index.html` yazın.
3. İstəsəniz brauzer menyusundan «Ana ekrana əlavə et» seçin.

**iPhone / iPad:** qovluğu «Fayllar» tətbiqinə köçürün, `index.html` faylını açın. Bəzən faylı «Safari-də aç» seçimi ilə açmaq lazım olur. Fayllar tətbiqi bəzi hallarda yalnız önizləmə göstərir. Bu halda qovluğu «Documents by Readdle» kimi fayl brauzeri ilə açmaq kömək edir.

## Qeydlər

- **Rekordlar və irəliləyiş** brauzerin yaddaşında (localStorage) saxlanılır. Brauzerin məlumatlarını silsəniz, itəcək.
- Ana səhifədəki «ən yaxşı nəticə» yazıları bəzi brauzerlərdə (xüsusən fayl bir qovluqdan açılanda) görünməyə bilər. Bu zaman oyunların özündə nəticələr yenə də saxlanılır.
- **Səs:** brauzerlər səsi ilk toxunuşdan sonra işə salır. Səs gəlmirsə, ekrana bir dəfə toxunun və ya səs düyməsini yoxlayın.
- Oyunlar internet olmadan, `file://` ilə birbaşa açılır. Server və ya quraşdırma lazım deyil.

## Telefonda daha rahat oynamaq üçün

- Oyunlar həm **şaquli**, həm də **üfüqi** (yan) vəziyyətdə işləyir.
- Telefon titrəyişi (vibrasiya) bəzi hadisələrdə işləyir (zərbə, tutma, qələbə). Səs düyməsini söndürsəniz, titrəyiş də dayanır.
- Ekran kilidlənəndə və ya başqa tətbiqə keçəndə səs avtomatik dayanır.
- Brauzer menyusundan **«Ana ekrana əlavə et»** seçsəniz, oyunlar ünvan sətri olmadan tam ekranda açılır.
- iPhone-da səs yalnız ilk toxunuşdan sonra başlayır və telefonun «səssiz» düyməsi açıqdırsa eşidilməyə bilər.
