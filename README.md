# Özkan REOS

Özkan Gün'ün emlak işletim sistemi (MVP). Statik sayfa; veri Supabase'de, erişim e-postayla giriş + veritabanındaki yetki listesiyle.

- Adres: https://gunozkan.github.io/reos/
- Ekranlar: Bugün, İlan, Ara (önerilen fiyat + FSBO yorumu), Huni, Kişi, Sevilay listesi
- Kodda yalnız Supabase'in herkese açık (publishable) anahtarı var; bütün veri `public.reos_*` fonksiyonlarından, giriş yapmış ve listede olan kullanıcıya döner.
