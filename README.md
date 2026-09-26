# Braylchi — o'rnatish

Braylchi — brayl kitob tayyorlash dasturi: PDF, Word yoki matndan Duxbury DBT (Uzbek Basic) uchun tayyor brayl.

**Eng so'nggi versiya:** o'ngdagi **Releases** → **Latest** (yoki [shu havola](https://github.com/rahmonsalom/braylchi-releases/releases/latest)). Sahifaning pastidagi **Assets** ro'yxatidan **faqat o'z qurilmangizga mos bitta faylni** yuklab oling.

## Qaysi faylni yuklab olish kerak

| Qurilma | Yuklab oling | O'rnatish |
|---|---|---|
| **Windows** | `Braylchi_…_x64-setup.exe` | Faylni ochib, ko'rsatmaga amal qiling. |
| **macOS** (Apple M1/M2… va Intel) | `Braylchi_…_universal.dmg` | Ochilgan oynada Braylchi belgisini **Applications** papkasiga suring. |
| **Linux** | `Braylchi_…_amd64.AppImage` | Faylga ishga tushirish ruxsatini bering (`chmod +x`) va oching. |
| **Android** (planshet) | `Braylchi_…_android.apk` | Planshetda faylni ochib **O'rnatish** ni bosing. |

Boshqa fayllar **yuklab olinmaydi** — ular o'rnatilgan ilovaning o'zi uchun:

| Fayl | Nima uchun |
|---|---|
| `…​.sig` | Imzo: ilova yangilanish fayli haqiqatan Braylchi muallifidan ekanini shu bilan tekshiradi. |
| `latest.json` | Ilova yangi versiya bor-yo'qligini shu fayldan biladi. |
| `…​.app.tar.gz` | macOS ilovasi o'zini yangilaganda yuklaydigan paket. |
| `…​.msi` | Windows uchun boshqa ko'rinishdagi o'rnatuvchi (tashkilotlarda ommaviy o'rnatish uchun). `setup.exe` yetarli. |
| `…​.deb`, `…​.rpm` | Linux tizim paketlari (Ubuntu/Debian, Fedora). AppImage o'rniga ishlatsa bo'ladi, lekin ular o'zi yangilanmaydi. |

## Birinchi ochilishdagi ogohlantirishlar

Braylchi pullik tijorat sertifikati bilan imzolanmagan, shuning uchun tizim birinchi marta ogohlantirishi mumkin. Bu dastur ishiga ta'sir qilmaydi.

- **Windows:** «Windows kompyuteringizni himoya qildi» oynasi chiqsa — **Batafsil** → **Baribir ishga tushirish**.
- **macOS:** «ochib bo'lmaydi» deyilsa — Applications papkasida Braylchi ustida **o'ng tugma → Ochish** → **Ochish**. Yoki *Tizim sozlamalari → Maxfiylik va xavfsizlik* → **Baribir ochish**.
- **Android:** planshet «noma'lum manbadan o'rnatish» ruxsatini so'raydi (fayl qaysi ilovada ochilgan bo'lsa, o'shanga — masalan brauzer yoki Fayllar) — ruxsat bering.

## Yangilanish

Bir marta o'rnatilgach, yangi versiyani qo'lda qidirish shart emas:

- **Kompyuter:** ilova yangi versiyani o'zi topadi va fonda yuklaydi. Tayyor bo'lgach, tepada **«↻ Yangilash uchun qayta ishga tushirish»** tugmasi chiqadi — qulay paytda bosing (ochiq loyiha saqlanadi). Qo'lda: *Yordam → Yangilanishni tekshirish*.
- **Android:** tepada **«↓ Yangi versiyani yuklab olish»** tugmasi chiqadi. Bosing, yuklangan faylni ochib **O'rnatish** ni bosing — eski versiya ustiga o'rnatiladi, ma'lumotlar saqlanib qoladi.

Yangilanishlar imzolangan: ilova faqat Braylchi muallifi imzolagan faylni o'rnatadi.

## Muhim: 0.2.0 dan oldingi sinov versiyalari

Planshetda 0.2.0 dan oldingi sinov (debug) versiyasi o'rnatilgan bo'lsa, uni **avval o'chiring**, keyin yangisini o'rnating — ular boshqa kalit bilan imzolangan. Keyingi versiyalar ustiga o'rnatiladi.
