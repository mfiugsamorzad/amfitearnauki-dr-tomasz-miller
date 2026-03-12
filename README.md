# aMFIteatr Nauki - Strona Wykładu (dr Tomasz Miller)

Repozytorium zawiera kod źródłowy strony internetowej typu *One-Page* promującej wykład otwarty pt. **„Niepojęta” matematyczność świata**, który wygłosi dr Tomasz Miller. Wydarzenie jest organizowane przez Radę Samorządu Studentów Wydziału Matematyki, Fizyki i Informatyki Uniwersytetu Gdańskiego w ramach cyklu **aMFIteatr nauki**.

Strona została zaprojektowana z myślą o urządzeniach mobilnych (jest w pełni responsywna), tak aby studenci skanujący kod QR z plakatów i ulotek mieli natychmiastowy i wygodny dostęp do wszystkich najważniejszych informacji.

## 🎯 Główne funkcje strony
* **Nawigacja One-Page Scroll**: Płynne przechodzenie do odpowiednich sekcji bez konieczności przeładowywania strony.
* **Kolorystyka uczelniana**: Design oparty na Księdze Identyfikacji Wizualnej UG (czcionka DM Sans, kolory granatowy `#0041D2` oraz pomarańczowy `#D26D00`).
* **Informacje o cyklu**: Historia sukcesu pierwszej edycji z prof. Andrzejem Draganem.
* **Sekcja logistyczna**: Czytelne informacje o dacie, miejscu i wstępie (dedykowane m.in. studentom Uczelni Fahrenheita - FarU).
* **Bezpośredni kontakt**: Aktywne linki kierujące na maila RSS MFI oraz profil na Instagramie.

## 📁 Struktura plików w repozytorium
Aby strona działała poprawnie, w repozytorium muszą znajdować się następujące pliki:
* `index.html` — główny plik zawierający cały kod strony i treść.
* `plakat.png` — główny plik graficzny z plakatem wydarzenia.
* `prelegent.jpg` — kwadratowe/prostokątne zdjęcie prelegenta (kod automatycznie przycina je do idealnego koła).
* `logo-ug.png`, `logo-mfi.png`, `logo-rss.png`, `logo-amfiteatr.png` — logotypy w kolorze białym umieszczone w górnym pasku nawigacyjnym.
* `instagram-logo.png` — ikona użyta w sekcji kontaktowej.

## ⚙️ Jak zaktualizować informacje na stronie?
1. Otwórz plik `index.html` w repozytorium.
2. Kliknij ikonę ołówka (Edit), aby wprowadzić zmiany w tekście (np. w dacie lub miejscu wydarzenia).
3. Po naniesieniu zmian zjedź na sam dół i kliknij zielony przycisk **Commit changes**.
4. GitHub Pages automatycznie zaktualizuje stronę w ciągu około 1-2 minut.

## 🚀 Hosting (GitHub Pages)
Strona jest hostowana darmowo za pomocą usługi GitHub Pages. 
Aby upewnić się, że strona działa:
1. Wejdź w zakładkę **Settings** w tym repozytorium.
2. Z menu po lewej stronie wybierz **Pages**.
3. Upewnij się, że w sekcji *Branch* wybrana jest gałąź `main` (lub `master`).

---
**Organizator:** Rada Samorządu Studentów Wydziału Matematyki, Fizyki i Informatyki UG (FarU)
**Kontakt:** samorzad.mfi@studms.ug.edu.pl | IG: [@mfiugsamorzad](https://instagram.com/mfiugsamorzad)
