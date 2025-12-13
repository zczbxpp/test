## Diagram działania aplikacji (flowchart)

Poniżej przedstawiono uproszczony diagram przepływu działania aplikacji do planowania nauki.

```mermaid
flowchart TD
    A[Użytkownik] --> B1[Interfejs UI]
    B1 --> B2[Lista zadań]
    B1 --> B3[Kalendarz]
    B1 --> B4[Statystyki]

    B1 --> C[Powiadomienia]
    C --> D[Logika biznesowa]
    
    B2 --> D
    B3 --> D
    B4 --> D

    D --> E[Baza danych]
```
---

### Legenda

- **Użytkownik** – osoba w wieku 18–25 lat korzystająca z aplikacji  
- **Interfejs UI** – widoki: lista zadań, kalendarz tygodniowy, statystyki  
- **Powiadomienia** – przypomnienia o zadaniach i wydarzeniach  
- **Logika biznesowa** – reguły tworzenia i edycji zadań, harmonogramy, obliczanie statystyk  
- **Baza danych** – przechowywanie zadań, wydarzeń i ustawień użytkownika  

---

### Wersja graficzna (opcjonalnie)

Diagram może zostać w przyszłości zapisany jako plik graficzny (PNG/JPG/SVG)  
i dołączony do repozytorium jako osobny zasób dokumentacyjny.
