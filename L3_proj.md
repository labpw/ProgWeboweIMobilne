### Zadanie: Aplikacja MVC – System Zarządzania Obiektami (max 5 punktów)

#### Opis Projektu:
Twoim zadaniem jest stworzenie elastycznej aplikacji w architekturze **MVC**, która będzie zarządzała wybranym przez Ciebie typem obiektów. Temat aplikacji jest dowolny (np. **sklep internetowy**, **biblioteka**, **system rezerwacji**, **zarządzanie pracownikami**). Dane dotyczące obiektów będą przechowywane w plikach w formacie **JSON**. Dodatkowo, aplikacja musi korzystać z szablonu dostarczonego z repozytorium [now-ui-dashboard](https://github.com/tomasz-trener/now-ui-dashboard-master), a wyniki (np. raporty) muszą być prezentowane w formie wykresów.

#### Wymagania Projektowe:

1. **CRUD na Elementach Aplikacji:**
   - Użytkownik powinien mieć możliwość **tworzenia**, **odczytywania**, **aktualizowania** i **usuwania** (CRUD) elementów wybranego typu.
   - Przykładowo, w aplikacji opartej na sklepie internetowym, elementami mogłyby być **produkty**, **klienci** lub **zamówienia**; w przypadku biblioteki, elementami mogłyby być **książki** czy **użytkownicy**.
   - **Dane** elementów muszą być przechowywane i odczytywane z plików **JSON**. Każda zmiana powinna automatycznie aktualizować pliki.

2. **Rozbudowana Funkcjonalność Przeglądania i Filtrowania:**
   - Użytkownicy aplikacji powinni mieć możliwość **przeglądania listy obiektów** oraz **filtrowania** i **sortowania** danych według różnych kryteriów. 
     - Przykładowo: w sklepie użytkownik może filtrować produkty po **cenie**, **kategorii** lub **dostępności**; w bibliotece, można filtrować książki po **autorze**, **gatunku** czy **roku wydania**.
   - Powinna być również opcja **wyszukiwania** konkretnych elementów na podstawie wybranego klucza (np. nazwa, ID).

3. **Architektura MVC:**
   - Aplikacja musi być napisana w architekturze **Model-View-Controller (MVC)**, co oznacza, że:
     - **Model**: Reprezentuje dane aplikacji, np. dane produktów, użytkowników, czy książek.
     - **View**: Odpowiada za prezentację danych użytkownikowi, bazując na dostarczonym szablonie [now-ui-dashboard](https://github.com/tomasz-trener/now-ui-dashboard-master).
     - **Controller**: Zajmuje się logiką biznesową, przetwarzaniem danych oraz odpowiednim kierowaniem użytkownika do widoków.
   - Każda operacja (np. dodanie elementu, edytowanie, usuwanie) powinna być realizowana poprzez odpowiednie akcje kontrolera.

4. **Użycie Szablonu z GitHub:**
   - W projekcie musisz wykorzystać **szablon** dostępny w repozytorium GitHub: [now-ui-dashboard](https://github.com/tomasz-trener/now-ui-dashboard-master). Szablon ten powinien być podstawą dla interfejsu użytkownika aplikacji.
   - Konieczne jest dostosowanie szablonu do obsługi CRUD oraz prezentacji danych w aplikacji. Widoki w aplikacji muszą być spójne z tym szablonem (np. formularze dodawania/edycji elementów, tabele z danymi, nawigacja).

5. **Generowanie Raportów w Formie Wykresów:**
   - W aplikacji powinna być możliwość **generowania raportów** w formie wykresów, korzystając z dostarczonego szablonu. Wykresy powinny prezentować dane zebrane w aplikacji.
     - Przykłady raportów:
       - W aplikacji sklepowej: **ilość zamówionych produktów** w czasie, **średnia cena produktów** w różnych kategoriach, **liczba zamówień** w danym miesiącu.
       - W aplikacji bibliotecznej: **liczba wypożyczeń** w danym okresie, **najbardziej wypożyczane książki**, **statystyki użytkowników**.
   - Wykresy mogą być generowane za pomocą bibliotek JavaScript dostępnych w szablonie (np. **Chart.js**).

 W ocenie brana będzie pod uwagę estatyka aplikacji!