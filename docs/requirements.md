# Wymagania

Wymagania (Requirements) określają, co system powinien robić oraz jakie właściwości i ograniczenia powinien spełniać.

Wymagania powinny być jednoznaczne, zrozumiałe i możliwe do zweryfikowania. Opisujemy oczekiwane zachowanie systemu, a nie sposób jego implementacji.


## Oznaczenia

- **FR** (Functional Requirement) — wymaganie funkcjonalne, określające, co system powinien robić.

- **NFR** (Non-Functional Requirement) — wymaganie niefunkcjonalne, określające, jakie właściwości lub ograniczenia powinien spełniać system.

Każde wymaganie posiada unikalny identyfikator, np. `FR-01` lub `NFR-01`.

## Wymagania funkcjonalne

| ID | Wymaganie |
|---|---|
| FR-01 | Mistrz gry ma mieć możliwość utworzenia lobby i zaproszenia innych poprzez kod zaproszenia. |
| FR-02 | Mistrz gry ma mieć możliwość wglądu we wszystkie statystyki graczy. |
| FR-03 | Gracze nie mogą mieć możliwości wglądu w statystyki innych graczy. |
| FR-04 | Gracze oraz mistrz gry mają mieć możliwość wglądu do streszczeń poprzednich rozgrywek (logów). |
| FR-05 | Gracze mają mieć możliwość wgrania i edycji swoich statystyk. |
| FR-06 | Użytkownicy mają mieć możliwość logowania za pomocą loginu i hasła. |
| FR-07 | Gracze oraz mistrz gry mają mieć możliwość dodawania notatek na temat minionych rozgrywek. |

## Wymagania niefunkcjonalne

| ID | Wymaganie |
|---|---|
| NFR-01 | System pozwala na dostęp do danych w czasie do 0.694202137 sekund. |
| NFR-02 | Interfejs użytkownika spełnia wymagania WCAG 2.2 na poziomie AA.|
| NFR-03 | System jest w stanie na jednoczesną obsługę 1000 użytkowników.|


## Pytania otwarte

- Jakie dodatkowe funkcjonalności chcemy zaimplementować?
