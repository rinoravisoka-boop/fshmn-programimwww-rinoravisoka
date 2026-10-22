# Java IV — Festivali që përshtatet në çdo ekran

## Çfarë realizova
Realizova faqen e festivalit me menu fleksibile me Flexbox dhe rrjetë aktivitetesh me CSS Grid. Teksti i gjatë mbahet brenda kartës përmes `overflow-wrap: break-word`.

## Testet

| Rezolucioni | Rezultati i Pritur | Rezultati i Marrë | Statusi |
| :--- | :--- | :--- | :--- |
| **360px** | 1 Kolonë, jo scroll horizontal | Shfaqet 1 kolonë pa scroll | ✅ Pass |
| **768px** | 2 Kolona | Shfaqen 2 kolona | ✅ Pass |
| **1280px** | 3 Kolona | Shfaqen 3 kolona | ✅ Pass |

## Reflektimi Individual

- **Flexbox**: E përdora te menuja (`nav ul`), sepse nevojitej renditje njëdimensionale në një rresht.
- **CSS Grid**: E përdora te struktura e kartave (`.grid`), sepse lehtëson renditjen në dy dimensione me kolona të barabarta (1, 2, ose 3 kolona).

## Burimet
Kodi u optimizua me ndihmën e AI për strukturë minimaliste.
