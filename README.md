
# 🌄 Pydev Valley 
> Silnik gry RPG 2D stworzony w Pythonie (Pygame-ce), z implementacją kamery Y-sort, integracją map TMX oraz modularną architekturą opartą na sprite’ach.

---

## ✨ Kluczowe funkcjonalności  
- 🎮 System renderowania oparty o Pygame-ce
- 📷 Kamera z sortowaniem Y (Y-sort camera) dla poprawnej głębi sceny
- 🧱 Integracja map kafelkowych TMX
- 🚧 Zaawansowany system kolizji
- 🧍 Obsługa stanów gracza (np. ruch, interakcje)
- 🔊 Zarządzanie dźwiękiem i zasobami gry
- 🧩 Modularna architektura oparta na sprite’ach

---

## 🛠️ Specyfikacja techniczna
- 🐍 Python: 3.11+
- 🎮 Silnik: Pygame-ce
- 🗺️ Formaty danych:
  * TMX — mapy kafelkowe
  * PNG — zasoby graficzne

---

## 📚 Główne biblioteki
- pygame-ce
- pytmx
- pyscroll

---

## 🚀 Instalacja i uruchomienie  

Klonowanie repozytorium

~~~bash  
git clone https://github.com/marlenalech/pydev-valley.git
~~~

Przejście do katalogu projektu  

~~~bash  
cd pydev-valley
~~~

Utworzenie środowiska wirtualnego  

~~~bash  
python -m venv venv
~~~

Aktywacja środowiska (Windows PowerShell)

~~~bash  
.\venv\Scripts\Activate.ps1
~~~

Instalacja zależności

~~~bash  
pip install -r requirements.txt
~~~

Uruchomienie projektu

~~~bash  
python main.py
~~~

---

## 🧠 Architektura projektu  

Projekt wykorzystuje podejście oparte na sprite’ach i komponentach, co umożliwia:

- separację logiki gry od renderowania
- łatwe rozszerzanie systemów (np. AI, walka, ekwipunek)
- modularność i lepszą organizację kodu  

---

## 📂 Źródło i inspiracja  

Implementacja bazuje na analizie systemów RPG udostępnionych przez Clear Code.
Projekt stanowi solidną bazę do dalszej rozbudowy o własne mechaniki i systemy gry.

---

## 🔮 Możliwe kierunki rozwoju

⚔️ System walki

🎒 Ekwipunek i przedmioty

🤖 AI przeciwników

💬 Dialogi i questy

🌍 Rozbudowa świata gry

---

## 📄 Licencja
Ten projekt może być rozwijany i dostosowywany według własnych potrzeb.

---

## ⭐ Wsparcie

Jeśli projekt okazał się pomocny, rozważ pozostawienie ⭐ na GitHubie!

___
Happy coding & game dev! 🎮🚀