
# 🎄 Xubuntu karácsonyra 🎄

Adományozott számítógépek automatizált Xubuntu 26 telepítése és konfigurálása Szeged környéki rászoruló gyerekeknek. Nyelvi modell közreműködésével két parancssor-szörnyeteg bash-szkript egyszerűsíti a beállításokat, a szoftvertelepítést és a Roblox (Sober) előkészítését. Gépenként majdnem 1-1 órát sikerült megtakarítani.

Karácsonyra hét, Szeged környékén élő, rászoruló gyerek asztali számítógépet kap Jézuskától.
A gépek, alkatrészek adományokból származnak. Nem csúcshardverek, minek is az, a konfigurációk legalább 4 GB RAM-mal rendelkeznek, a processzorok pedig az Intel Pentium G630-tól egészen az Intel Core i3-8100-ig terjednek.

# 🐧 cél:
A Linux terjesztése, a Roblox megunása, olyan számítógépeket átadni, amelyekkel a gyerekek tanulhatnak, filmezhetnek és netezhetnek..

A választás a Xubuntu 26 rendszerre esett. Mert nem és nem, nincs vita, a Xubuntu a legjobb, volt, lesz, éppen pont az!
A Roblox futtatását a Sober biztosítja, ahol a hardveres kompatibilitás ezt lehetővé teszi. Egy gép kivétel: annak CPU-ja nem támogatja az SSE4.2 emulálását, így azon a Sober nem használható.

Két parancssor-szörnyeteg könnyíti meg a munkát, melyeket a nyelvi modellel sikerült összerakni. Gépenként így majdnem 1 óra spórolható meg. A 3 bash-t egyelőre nem sikerült összefűzni, hibázott. Szóval van hová fejlődni.

# 🎅 1. lépés | Xubuntu 26 install Ventoy-jal
Automatikus beléptetés. 2026 nyári ISO.

# ⛄ 2. lépés | öt fájl bemásolása a Letöltések mappába:
- bookmarks.html, birka.png, roblox_icon.png, panel.tar.bz2, Journey_home_by_Juliette_Taka.png

![Journey_home_by_Juliette_Taka.png](Journey_home_by_Juliette_Taka.png)

# ❄️ 3. lépés | parancssor-szörnyeteg I.
- Magyar nyelvi környezet telepítése.
- Firefox ESR telepítése Mozilla PPA-ból, Snap Firefox eltávolítása.
- Numix ablakkeret, Adwaita-dark téma.
- Értesítések időtartamának módosítása 3 másodpercre.
- Kép- és szövegfájlok alapértelmezett alkalmazásainak beállítása.
- Felhasználói avatar [birka.png] és háttérkép beállítása [Juliette Taka Journey home c. festménye a Xubuntu 24-ből].
- Flathub és Sober telepítése Roblox-hoz.
- ..

# 🦌 4. lépés | parancssor-szörnyecske
- sudo apt update && sudo apt install -y 7zip adb audacity cpufrequtils cryptsetup dosfstools exiftool exfatprogs fastboot ffmpeg gparted gvfs gufw heimdall-flash l3afpad lvm2 mpv mtools mtpaint ntfs-3g pcmanfm photoflare rar synaptic thunar-gtkhash thunar-volman ucommon-utils udisks2 unrar unzip usbutils viewnior vlc vnstat wavemon zram-tools yt-dlp

Ne feledjük, a LibreOffice alap a Xubuntu-ban is! Ami sokkal-de-sokkal jobb, mint a Word/Excel!

# ⭐ 5. lépés | parancssor-szörnyeteg II.
- Xfce panelprofil visszaállítása egy korábbi mentésből, amit a Letöltések mappába raktunk.
- Sober asztali ikon létrehozása.
- Firefox belakása: uBlock Origin, dedikált Bookmarks.html [pld.: Kék Vonal], Startpage kereső, Wikipedia kezdőlap..
- Fájltársítások.
- Hibák és sikeres lépések összesítése.
- ..

# 🔔 6. lépés | hab a tortán, meteorcsillag, egyeseknél Halálcsillag a karácsonyfa csúcsán
sudo ufw enable - És megszólalnak a karácsonyi harangok.

Ezek percek alatt lefutnak, majd néhány apróság kézzel, mint például a menulibre, videó és hang teszt, Roblox ikon + tesztindítás, Thunar Recent törlése és 32px-es oldalsáv, AboutMe igazítás..

Ami bekavarhat: a folyamat elején lefutó frissítés. Szépen megkérjük a nyelvi modellt, hátrapakolja..

# 🎁 GAFAM?
Semmiképpen se GAFAM-ozzuk össze magunkat, főleg ne a kiskorúakat! Alábbi, egy kakukktojást tartalmazó könyvjelző eszköztár települ fel a Firefox ESR-re, mint "mail", "közösség"..:
- hiroldal, chatgpt.com, deepai.org, disroot.org, hu.wikipedia.org, kek-vonal.hu, mastodon.social, mega.io, mixcloud.com, murena.io, openstreetmap.org, perplexity.ai, protectedtext.com, qubit.hu, roblox.com, startpage.com, szotar.sztaki.hu, telegram.org, youtube.com

Mostanság nagyot bukott a Disroot, de példaértékűen kezelik! Alternatívaként a Murena mellett az astermail.org-ot ajánlom.

A nyelvi modell elvitathatatlan érdemei mellett a protectedtext.com is segítségemre volt.

# 🎄 Utóirat

A G630 is ember, a gép szerint. Ami téved, de állja a sarat - kevesebbet téved és jobban állja, mint én. Gazdagabb lettem egy zsömlszacskónyi pormacskával.
És mi történik, ha valami elromlik? Három ágens ücsörög a könyvjelzők között: a gyerek tanul!

sudo apt install happiness

