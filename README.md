# 🌤️ Aplikacja Pogodowa (Python)

Prosta i interaktywna aplikacja konsolowa napisana w języku Python, która pozwala na sprawdzenie aktualnej pogody dla dowolnego miasta na świecie. Projekt został stworzony w celach edukacyjnych, aby zaprezentować podstawy pracy z zewnętrznym API.

## 🚀 Funkcjonalności
* Pobieranie aktualnej temperatury w stopniach Celsjusza.
* Wyświetlanie opisu warunków pogodowych w języku polskim.
* Obsługa błędów (np. błędna nazwa miasta lub brak autoryzacji).
* Interaktywny interfejs w konsoli (program sam pyta o nazwę miasta).

## 🛠️ Technologie
* **Język:** Python 3
* **Biblioteki:** `requests`
* **API:** [OpenWeatherMap API](https://openweathermap.org/) (zwracające dane w formacie JSON)

## 💻 Jak uruchomić projekt lokalnie?

1. **Sklonuj repozytorium na swój komputer:**
   ```bash
  git clone [https://github.com/maaniek697/AplikacjaPogodowa.git](https://github.com/maaniek697/AplikacjaPogodowa.git)
   
Przejdź do folderu z projektem i zainstaluj wymagane biblioteki:

Bash
pip install requests

3. **Zdobądź klucz API:**
   * Załóż darmowe konto na stronie [OpenWeatherMap](https://openweathermap.org/).
   * Wygeneruj swój klucz API w ustawieniach konta.
   * W pliku `script.py` (lub `pogoda.py`) podmień zmienną `klucz_api` na swój własny klucz.
4. **Uruchom aplikację:**
   ```bash
   python script.py
