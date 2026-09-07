# Zrzuty użyte w README

Przechwycone z tego repozytorium uruchomionego lokalnie
(`python3 -m http.server`), Firefox headless, okno 1400 px.

| Plik | Podstrona | Dlaczego akurat ta |
|---|---|---|
| `01-wwr.png` | Wczesne wspomaganie rozwoju | Pokazuje typografię, plakietki i przyciski. **Bez twarzy** — w kadrze same dłonie |
| `02-kontakt.png` | Kontakt | Układ kart z danymi. **Bez osób.** Przycięty nad wierszem z NIP-em i numerem konta klienta |
| `03-blog.png` | Blog | Własny typ treści. Zdjęcie wpisu to **rysowany plakat**, nie fotografia dzieci |

## Czego tu świadomie nie ma

- **Strona główna** — w kadrze twarze dzieci.
- **Program** — w kadrze twarz dziecka.
- **Nauczyciele, Galeria** — wizerunki pracowników i dzieci.

Zdjęcia są publiczne na stronie klienta, ale zgoda klienta na publikację u siebie
to nie to samo co zgoda na użycie w cudzym portfolio. Do materiałów sprzedażowych
idą wyłącznie kadry bez osób.

## Uwaga o przechwytywaniu

Cztery zdjęcia na blogu mają `loading="lazy"`, więc przy zwykłym zrzucie headless
**nie ładują się wcale** i strona wygląda na zepsutą. To artefakt narzędzia, nie
błąd strony. Zrzuty powstały z `dom.image-lazy-loading.enabled=false` w profilu
Firefoksa; animacje wejścia odsłonięte przez `ui.prefersReducedMotion=1`.
