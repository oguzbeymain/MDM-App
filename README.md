<p align="center">
  <img src="media/mdm-logo.png" width="128" alt="MDM logo">
</p>

<h1 align="center">MDM</h1>
<p align="center"><strong>Muck Download Manager</strong></p>
<p align="center">A fast, native Windows download manager with a dark studio look — catch links from your browser, pull YouTube and torrents, keep going in the background.</p>

<p align="center">
  <a href="#english">English</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="#türkçe">Türkçe</a>
</p>

<p align="center">
  <a href="https://github.com/oguzbeymain/MDM-App/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/oguzbeymain/MDM-App?style=for-the-badge&color=FF6B00&label=Download"></a>
  <a href="https://github.com/oguzbeymain/MDM-App/releases/latest"><img alt="Windows" src="https://img.shields.io/badge/Windows-x64-111111?style=for-the-badge&logo=windows&logoColor=white"></a>
</p>

<p align="center">
  <img src="media/mdm-hero.png" width="920" alt="MDM — Muck Download Manager">
</p>
<p align="center"><a href="https://github.com/oguzbeymain"><strong>oguzbeymain</strong></a></p>

<p align="center">
  <img src="media/mdm-main.png" width="920" alt="MDM main window">
</p>

---

## English

MDM is built for people who download a lot and do not want the browser to own the file. Click in Chrome, Edge, or Firefox — MDM takes over, shows a compact session, and writes the file where you asked.

### Why it feels different
- **Native Windows app** — not a web wrapper. Dark UI, orange accent, categories on the left, speed on the row.
- **Browser capture** — intercept downloads and send them to MDM instead of the default folder.
- **Video that actually finishes** — YouTube, HLS, and similar streams go through a dedicated engine instead of a broken `.mp4` stub.
- **Torrents included** — magnet links, `.torrent` files, or the full content. You choose.
- **Stays out of the way** — tray, optional complete balloons, and **Game mode** so fullscreen play is not interrupted.
- **No runtime hunt** — the setup is self-contained. You do not install .NET first.

### Install
1. Grab **[MDM-Setup](https://github.com/oguzbeymain/MDM-App/releases/latest)** (`MDM-Setup-1.0.47.exe`).
2. Run it. MDM lands in your user Programs folder — no admin circus, no extra .NET.
3. Open **Settings → Browser extension** and add it to the browser you actually use.

Portable zip (`MDM-1.0.47-win-x64.zip`) is on the same release if you prefer not to use Setup.

### In the box
| | |
|:--|:--|
| HTTP / HTTPS | Multi-connection downloads, resume, smart rename |
| Video | YouTube, HLS, DASH via yt-dlp when the file is not a direct link |
| Torrents | Magnet, `.torrent` only, or full swarm download |
| Library | Categories, search, dark / light theme, 13 UI languages |
| Power | Speed limits, schedule, queue, LAN remote API |

### Requirements
Windows 10 / 11 **64-bit**. Setup is self-contained.

Source: [oguzbeymain/MDM-Source](https://github.com/oguzbeymain/MDM-Source)

---

## Türkçe

MDM, tarayıcının indirme klasörüne mahkûm olmak istemeyenler için. Chrome, Edge veya Firefox’ta tıklarsın; MDM devralır, küçük oturum penceresini açar, dosyayı senin seçtiğin yere yazar.

### Neden ayrı duruyor
- **Gerçek Windows uygulaması** — web kabuğu değil. Koyu arayüz, turuncu vurgu, solda kategoriler, satırda hız.
- **Tarayıcıdan yakalama** — indirmeyi varsayılan klasöre bırakmak yerine MDM’ye alır.
- **Video yarım kalmaz** — YouTube, HLS ve benzeri akışlar ayrı motorla iner; bozuk `.mp4` parçası değil.
- **Torrent de var** — magnet, yalnızca `.torrent` dosyası veya tam içerik. Sen seçersin.
- **Oyunun üstüne binmez** — tepsi, isteğe bağlı bildirim, **Oyun modu** ile tam ekranda pencere patlamaz.
- **.NET aratmaz** — setup kendi runtime’ını taşır.

### Kurulum
1. **[MDM-Setup](https://github.com/oguzbeymain/MDM-App/releases/latest)** dosyasını indir (`MDM-Setup-1.0.47.exe`).
2. Çalıştır. MDM kullanıcı Programs klasörüne kurulur — yönetici istemez, ayrı .NET de yok.
3. **Ayarlar → Tarayıcı eklentisi** üzerinden kullandığın tarayıcıya eklentiyi ekle.

Kurulum istemezsen aynı sürümde taşınabilir zip de var: `MDM-1.0.47-win-x64.zip`.

### Neler var
| | |
|:--|:--|
| HTTP / HTTPS | Çok kanallı indirme, devam ettirme, akıllı yeniden adlandırma |
| Video | Doğrudan dosya değilse YouTube / HLS / DASH (yt-dlp) |
| Torrent | Magnet, yalnızca `.torrent`, veya tam içerik |
| Kütüphane | Kategoriler, arama, koyu / açık tema, 13 dil |
| Güç | Hız limiti, zamanlama, kuyruk, LAN uzaktan API |

### Gereksinim
Windows 10 / 11 **64-bit**. Setup kendi içinde çalışır.

Kaynak kod: [oguzbeymain/MDM-Source](https://github.com/oguzbeymain/MDM-Source)
