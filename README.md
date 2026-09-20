# AzMessage

**AzMessage**, modern, sade ve güvenlik odaklı bir altyapı üzerine geliştirilmiş native bir Android mesajlaşma uygulamasıdır.

AzMessage; kullanıcıların internet üzerinden birbirleriyle mesajlaşabilmesini sağlayan, performans, kararlılık, sadelik ve güvenlik öncelikleri göz önünde bulundurularak geliştirilen bağımsız bir Android projesidir.

Projenin geliştirme, tasarım ve teknik altyapı çalışmaları **Muhammed** tarafından bağımsız olarak yürütülmektedir.

Bu GitHub deposu, **AzMessage'in resmî dağıtım merkezi ve proje merkezidir.** Kararlı ve beta sürümleri burada yayınlanır. Projeyle ilgili gelişmeler ve duyurular ise resmî Telegram ve WhatsApp kanallarımız üzerinden paylaşılır.

---

## 🛠️ Teknik Altyapı ve Mimari

AzMessage geliştirilirken performans, kararlılık, düşük kaynak tüketimi, sadelik ve güvenlik temel öncelikler olarak ele alınmaktadır.

### 💻 Geliştirme

- Native Android altyapısı kullanılmaktadır.
- Uygulamanın temel kod yapısı **Java 8** ile geliştirilmiştir.
- Gereksiz ve uygulamayı şişirebilecek üçüncü taraf kütüphanelerden mümkün olduğunca kaçınılmaktadır.
- Android'in yerleşik API'lerinden ve güvenilir platform bileşenlerinden yararlanılmaktadır.
- Uygulama mümkün olduğunca düşük kaynak tüketimi ve akıcı kullanım hedeflenerek geliştirilmektedir.

### 📱 Android Desteği

AzMessage, **Android API 21 ve üzeri** cihazları hedeflemektedir.

Farklı Android sürümleri, ekran boyutları ve cihaz özellikleri göz önünde bulundurularak geniş cihaz uyumluluğu sağlanması amaçlanmaktadır.

### ⚡ Gerçek Zamanlı Mesajlaşma

Anlık mesajlaşma ve veri senkronizasyonu için **Firebase Realtime Database** altyapısından yararlanılmaktadır.

Mesaj gönderme ve alma, mesajların senkronizasyonu, okunma durumları ve bazı çevrim içi durum özellikleri gerçek zamanlı veri altyapısı üzerinden gerçekleştirilmektedir.

### 🎨 Arayüz

AzMessage, Android'in modern tasarım anlayışından yararlanan özel XML arayüzleriyle tasarlanmıştır.

Arayüz geliştirilirken:

- Sade ve anlaşılır kullanım
- Akıcı kullanım deneyimi
- Farklı ekran boyutlarına uyumluluk
- Gereksiz görsel karmaşadan uzak tasarım
- Mesajlaşma deneyimine odaklanan kullanıcı arayüzü

gibi unsurlar ön planda tutulmaktadır.

### 🔐 Güvenlik

Güvenlik, AzMessage'in geliştirme sürecindeki temel önceliklerden biridir.

Kimlik doğrulama, veri erişimi, kullanıcı yetkilendirme, mesajlaşma ve uygulama içindeki diğer hassas işlemlerde mümkün olduğunca güvenli Android ve Firebase mekanizmalarından yararlanılmaktadır.

Güvenlik altyapısı geliştirme sürecinin devam eden bir parçasıdır. Yeni sürümlerde güvenlik iyileştirmeleri ve ek güvenlik önlemleri uygulanabilir.

---

## 📦 Resmî Dağıtım

AzMessage'in **resmî dağıtım merkezi bu GitHub deposudur.**

Kararlı sürümler ve beta/test sürümleri GitHub üzerindeki **Releases** bölümünde yayınlanır.

> **Resmî APK indirmek için GitHub Releases bölümünü kullanmanız önerilir.**

İnternet üzerinde AzMessage adıyla bulunan ancak resmî kanallarımız üzerinden yayınlanmayan APK dosyaları **resmî AzMessage sürümleri değildir.**

Üçüncü taraflar tarafından değiştirilmiş, yeniden paketlenmiş veya farklı kaynaklardan dağıtılmış APK'ların güvenliği ve bütünlüğü garanti edilmez.

---

## 📢 Resmî Kanallar

AzMessage'in GitHub dışında iki resmî duyuru ve iletişim kanalı bulunmaktadır.

### Telegram

Telegram kanalımızda proje haberleri, güncellemeler, duyurular ve **APK sürümleri** paylaşılmaktadır.

**Telegram:**  
https://t.me/AzMessageMaqa

Telegram kanalında APK paylaşılabildiği için yeni sürümleri ve güncellemeleri takip etmek isteyen kullanıcılar bu kanalı da kullanabilir.

### WhatsApp

WhatsApp kanalımız ağırlıklı olarak **haberler, güncellemeler, önemli bilgiler ve bağlantılar** paylaşmak amacıyla kullanılmaktadır.

> **WhatsApp kanalında APK dosyaları paylaşılmamaktadır.**

**WhatsApp:**  
https://whatsapp.com/channel/0029VbD7SytDJ6GzSVDNiP2Y

---

## 🔒 Telif Hakkı ve Lisans

**AzMessage kapalı kaynaklı (Closed Source) bir projedir.**

AzMessage'in kaynak kodları, uygulama mimarisi, özgün tasarımları, proje içerisinde oluşturulan özgün içerikleri ve diğer proje varlıkları izinsiz kullanım ve yeniden dağıtıma karşı korunmaktadır.

AzMessage'i bir son kullanıcı olarak **kullanmanız tamamen serbesttir.**

### ✅ Kullanıcıların Yapabileceği İşlemler

Kullanıcılar AzMessage'i:

- Telefonlarına yükleyebilir,
- Mesajlaşmak için kullanabilir,
- Kişileriyle iletişim kurabilir,
- Uygulamanın sunduğu özelliklerden yararlanabilir,
- Kararlı sürümleri kullanabilir,
- Beta/test sürümlerine katılabilir,
- Uygulamayı kişisel amaçlarla kullanabilir.

AzMessage'in normal kullanıcı olarak kullanılması herhangi bir şekilde kısıtlanmamaktadır.

### ❌ İzinsiz Yapılması Yasaklanan İşlemler

Proje sahibinin açık yazılı izni olmadan aşağıdaki işlemlere izin verilmemektedir:

- AzMessage'in kaynak kodlarının kopyalanması,
- Kaynak kodlarının başka projelerde kullanılması,
- Uygulamanın decompile edilerek kaynak kodunun veya kod yapısının yeniden oluşturulması,
- Uygulamanın reverse engineering amacıyla incelenmesi,
- APK dosyasının değiştirilmesi,
- APK'nın yeniden paketlenmesi,
- Modifiye edilmiş AzMessage sürümleri oluşturulması,
- Değiştirilmiş APK'ların başka kişilere dağıtılması,
- AzMessage kodlarının veya mimarisinin başka bir uygulamaya aktarılması,
- AzMessage'in özgün tasarımlarının başka projelerde izinsiz kullanılması,
- AzMessage'e ait özgün içeriklerin başka uygulamalarda veya projelerde kullanılması,
- Değiştirilmiş veya kopyalanmış bir sürümün resmî AzMessage sürümü gibi sunulması,
- AzMessage adı kullanılarak sahte veya yetkisiz sürümlerin dağıtılması,
- Projeye ait kodların, dosyaların veya diğer özgün içeriklerin başka yazılımların parçası olarak yeniden yayınlanması.

Bu kısıtlamalar **uygulamanın normal kullanımını değil**, AzMessage yazılımının ve projeye ait özgün içeriklerin izinsiz şekilde kopyalanmasını, değiştirilmesini, yeniden dağıtılmasını veya başka projelerde kullanılmasını kapsamaktadır.

---

## ⚠️ Değiştirilmiş ve Yetkisiz APK'lar

İnternet üzerinde AzMessage adıyla dağıtılan ancak GitHub Releases, Telegram veya AzMessage tarafından belirtilen diğer resmî kaynaklardan yayınlanmayan APK dosyaları **resmî AzMessage sürümü olarak kabul edilmez.**

Üçüncü taraflar tarafından:

- Değiştirilmiş,
- Yeniden paketlenmiş,
- İmzalanmış,
- Kaynak kodu değiştirilmiş,
- Ek özellikler eklenmiş veya çıkarılmış

APK dosyaları AzMessage'in resmî sürümleri değildir.

Bu tür APK'ların güvenliği, bütünlüğü, içerisinde yapılan değişiklikler veya kullanıcı verileri üzerindeki davranışları proje tarafından garanti edilmez.

Kullanıcıların güvenilir bir sürüm kullandığından emin olmak için APK'ları yalnızca **resmî GitHub Releases veya resmî Telegram kanalımızdan** edinmeleri önerilir.

---

## 📜 Proje ve Telif Bilgileri

**Proje:** AzMessage  
**Geliştirici:** Muhammed  
**Kaynak Kodu:** Closed Source  
**Proje:** © 2026 AzMessage

AzMessage'in geliştirme ve yönetimi **Muhammed** tarafından yürütülmektedir.

"AzMessage" adı, uygulamanın kaynak kodları, özgün tasarımları ve projeye ait diğer özgün içerikler izin alınmadan kopyalanamaz, yeniden dağıtılamaz veya başka projelerde kullanılamaz.

---

## 📥 İndirme

AzMessage'in güncel kararlı ve beta sürümlerine ulaşmak için GitHub deposundaki:

**Releases**

bölümünü ziyaret edebilirsiniz.

Resmî APK dağıtım noktaları:

- **GitHub Releases:** Resmî dağıtım merkezi
- **Telegram:** APK, güncellemeler ve duyurular
- **WhatsApp:** Haberler, bilgiler, güncellemeler ve bağlantılar

Resmî kaynaklar dışında dağıtılan AzMessage APK'larının resmî olmadığı unutulmamalıdır.

---

## 👨‍💻 AzMessage

AzMessage, bağımsız olarak geliştirilen bir Android mesajlaşma projesidir.

**Kurucu & Geliştirici:** Muhammed  
**Kaynak kodu:** Kapalı kaynak  
**Resmî dağıtım merkezi:** GitHub  
**Resmî Telegram:** https://t.me/AzMessageMaqa  
**Resmî WhatsApp:** https://whatsapp.com/channel/0029VbD7SytDJ6GzSVDNiP2Y
