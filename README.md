Federal Webhook Message Sender - Dokumentacja

[Strona demo](https://sites.google.com/view/dojwebhook?usp=sharing)


Opis projektu

Federal Webhook Message Sender to oficjalne narzędzie komunikacyjne pod serwery rp dla DOJ, które umożliwia bezpieczne wysyłanie wiadomości poprzez webhooki. Aplikacja została zaprojektowana z myślą o wymaganiach bezpieczeństwa i profesjonalizmu instytucji rządowych, z wykorzystaniem amerykańskiej kolorystyki narodowej (niebieski, czerwony, biały) i formalnej typografii.

Kluczowe funkcje

1. Bezpieczne wysyłanie wiadomości
   - Wsparcie dla webhooków Discord i innych platform
   - Automatyczne formatowanie wiadomości dla Discord embed
   - Obsługa załączników w postaci linków do dokumentów

2. Profesjonalny interfejs
   - Oficjalny styl rządowy z flagą USA
   - Responsywny design działający na różnych urządzeniach
   - Formalna typografia (font Georgia)

3. System powiadomień
   - Toast notifications dla sukcesów i błędów
   - Animowany przycisk wysyłania z loaderem
   - Walidacja formularza przed wysłaniem

4. Bezpieczeństwo
   - Klasyfikacja "Public" dla komunikacji
   - Ostrzeżenia o nieautoryzowanym dostępie
   - Wszystkie operacje wykonywane po stronie klienta

Technologie

- HTML5 - struktura aplikacji
- CSS3 - styling z animacjami i gradientami
- JavaScript (ES6) - logika działania i komunikacja z API
- Google Fonts - typografia (Georgia)

Instalacja i użycie

Aplikacja działa bezpośrednio w przeglądarce - nie wymaga instalacji ani serwera backendowego:

1. Pobierz plik `index.html`
2. Otwórz w przeglądarce internetowej
3. Wprowadź:
   - URL webhooka
   - Temat wiadomości
   - Treść wiadomości
   - (Opcjonalnie) Link do dokumentu
4. Kliknij "Wyślij Wiadomość"
