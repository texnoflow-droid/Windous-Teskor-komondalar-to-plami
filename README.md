# Windows Buyruqlari To'plami (CMD & Run) 🚀

Ushbu loyiha Windows operatsion tizimida ishlashni tezlashtiradigan eng foydali va kerakli buyruqlar to'plamini o'z ichiga oladi. Buyruqlar CMD (Command Prompt) va Run (Win + R) oynasi uchun alohida kategoriyalarga ajratilgan.

---

## 📁 Mundarija
1. [CMD Buyruqlari](#-cmd-buyruqlari)
2. [Run (Win + R) Buyruqlari](#-run-win--r-buyruqlari)
3. [Xavfsizlik va Parollar](#-xavfsizlik-va-parollar)
4. [Tizim Diagnostikasi](#-tizim-diagnostikasi)

---

## 💻 CMD Buyruqlari
Batafsil ma'lumot uchun:
- [CMD Fayl va Papkalar](Windows_Buyruqlari/CMD_Fayl_Papkalar.md)
- [CMD Tizim Ma'lumotlari](Windows_Buyruqlari/CMD_Tizim_Malumot.md)
- [CMD Tarmoq Buyruqlari](Windows_Buyruqlari/CMD_Tarmoq_Buyruqlari.md)
- [CMD Foydalanuvchilar](Windows_Buyruqlari/CMD_Foydalanuvchilar.md)
- [CMD Disk Parvarishi](Windows_Buyruqlari/CMD_Disk_Parvarishi.md)
- [CMD Qo'shimcha Buyruqlar](Windows_Buyruqlari/CMD_Qoshimcha_Foydali.md)

### 📁 Fayl va papkalar bilan ishlash
| Buyruq              | Vazifasi                                       |
| ------------------- | ---------------------------------------------- |
| `dir`               | Joriy papkadagi fayl va papkalarni ko‘rsatadi. |
| `cd`                | Papkani o‘zgartiradi (misol: `cd Documents`).  |
| `cd..`              | Bir darajaga yuqoriga chiqadi.                 |
| `md` yoki `mkdir`   | Yangi papka yaratadi (`mkdir yangi_papka`).    |
| `del`               | Faylni o‘chiradi (`del fayl.txt`).             |
| `rmdir` yoki `rd`   | Bo‘sh papkani o‘chiradi.                       |
| `copy`              | Faylni nusxalaydi (`copy fayl.txt D:\Zahira`). |
| `move`              | Faylni boshqa joyga ko‘chiradi.                |
| `rename` yoki `ren` | Fayl yoki papkani qayta nomlaydi.              |

### ⚙️ Tizim haqidagi ma'lumotlar
| Buyruq                        | Vazifasi                                   |
| ----------------------------- | ------------------------------------------ |
| `systeminfo`                  | Kompyuter haqida to‘liq texnik ma'lumot.   |
| `hostname`                    | Kompyuter nomini ko‘rsatadi.               |
| `tasklist`                    | Hozir ishlayotgan dasturlar ro‘yxati.      |
| `taskkill /IM appname.exe /F` | Dastur majburan yopiladi.                  |
| `ver`                         | Windows versiyasini ko‘rsatadi.            |
| `echo %USERNAME%`             | Kompyuter foydalanuvchi nomini ko‘rsatadi. |
| `echo %DATE% %TIME%`          | Sana va vaqtni ko‘rsatadi.                 |

### 🌐 Tarmoq buyruqlari
| Buyruq            | Vazifasi                                          |
| ----------------- | ------------------------------------------------- |
| `ipconfig`        | IP manzil va tarmoq adapteri ma'lumotlari.        |
| `ping google.com` | Internetga ulanayotganligini tekshiradi.          |
| `netstat`         | Tarmoq portlari va ulangan manbalarni ko‘rsatadi. |
| `tracert`         | Paket qayerdan o‘tayotganini ko‘rsatadi.          |
| `nslookup`        | DNS haqida ma'lumot beradi.                       |
| `arp -a`          | LANdagi qurilmalarni ko‘rsatadi.                  |

---

## 🏃‍♂️ Run (Win + R) Buyruqlari
Batafsil ma'lumot uchun:
- [Run Shell Buyruqlari](Windows_Buyruqlari/Run_Shell_Buyruqlari.md)
- [Run Mashhur Tizim](Windows_Buyruqlari/Run_Mashhur_Tizim.md)
- [Run Maxfiy Buyruqlar](Windows_Buyruqlari/Run_Maxfiy_Buyruqlar.md)
- [Run Dasturchilar Uchun](Windows_Buyruqlari/Run_Dasturchilar_Uchun.md)
- [Run Boshqarish Buyruqlari](Windows_Buyruqlari/Run_Boshqarish_Buyruqlari.md)
- [Run Tozalash va Optimallashtirish](Windows_Buyruqlari/Run_Tozalash_Optimallashtirish.md)
- [Run Diagnostika va Ma'lumot](Windows_Buyruqlari/Run_Diagnostika_Malumot.md)
- [Run Xavfsizlik va Parollar](Windows_Buyruqlari/Run_Xavfsizlik_Parol.md)
- [Run Yordamchi Ilovalar](Windows_Buyruqlari/Run_Yordamchi_Ilovalar.md)

### 🧠 shell: Buyruqlari — Ilovalar va papkalarni ochish
| Buyruq                      | Vazifasi                                                 |
| --------------------------- | -------------------------------------------------------- |
| `shell:appsfolder`          | Barcha ilova va dasturlar ro‘yxatini ko‘rsatadi          |
| `shell:startup`             | Windows boshlanishida ishga tushadigan dasturlar papkasi |
| `shell:recent`              | Yaqinda ochilgan fayllar ro‘yxati                        |
| `shell:downloads`           | Yuklab olingan fayllar papkasi                           |
| `shell:mycomputerfolder`    | Bu "This PC" oynasini ochadi                             |
| `shell:controlpanel`        | Klassik boshqaruv paneli                                 |

### ⚙️ Mashhur tizim buyruqlari
| Buyruq         | Ma'nosi                                                            |
| -------------- | ------------------------------------------------------------------ |
| `msconfig`     | Tizim konfiguratsiyasi (avto-ishga tushish, yuklanish sozlamalari) |
| `services.msc` | Xizmatlar boshqaruvi (services)                                    |
| `taskmgr`      | Task Manager (Vazifalar dispetcheri)                               |
| `regedit`      | Registry Editor (Reestr tahrirlovchisi)                            |
| `devmgmt.msc`  | Qurilma dispetcheri (Device Manager)                               |

---

## 🔐 Xavfsizlik va Parollar
| Buyruq                   | Nima qiladi                                                        |
| ------------------------ | ------------------------------------------------------------------ |
| `net user`               | Barcha foydalanuvchilar ro‘yxatini ko‘rsatadi.                     |
| `netplwiz`               | Parolni avtomatik o‘tishni sozlash oynasi                          |
| `lusrmgr.msc`            | Mahalliy foydalanuvchilar va guruhlar                              |
| `secpol.msc`             | Mahalliy xavfsizlik siyosatlari                                    |

---

## 🛠 Tizim Diagnostikasi
| Buyruq               | Nima qiladi                                                 |
| -------------------- | ----------------------------------------------------------- |
| `dxdiag`             | DirectX diagnostika vositasi                                |
| `msinfo32`           | Tizim haqida keng ma’lumot                                  |
| `perfmon /report`    | Kompyuterning ishlash hisobotini yaratadi                   |
| `sfc /scannow`       | Tizim fayllarini tekshiradi va tuzatadi                     |

---

## 🧹 Tozalash va Optimallashtirish
| Buyruq           | Nima qiladi                                                  |
| ---------------- | ------------------------------------------------------------ |
| `cleanmgr`       | Diskni tozalash oynasi                                       |
| `%temp%`         | Vaqtinchalik fayllar papkasi                                 |
| `rstrui.exe`     | System Restore (tizimni tiklash) oynasi                      |
| `powercfg.cpl`   | Quvvat sozlamalari                                           |

---

## 👨‍💻 Muallif
Ushbu to'plam Windows foydalanuvchilari uchun yordam sifatida tayyorlandi. GitHub'da ulashing va foydalaning! 🌟
