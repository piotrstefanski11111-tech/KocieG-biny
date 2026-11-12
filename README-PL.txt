KOCIE GŁĘBINY — projekt aplikacji Android

Gra HTML została opakowana w natywną aplikację Android (WebView). Kod gry
pozostaje lokalnie w aplikacji, działa bez internetu i zachowuje zapis
postępu przez localStorage.

NAJPROŚCIEJ ZBUDOWAĆ APK:
1. Rozpakuj ZIP.
2. Otwórz folder KocieGlebiny-Android w Android Studio.
3. Poczekaj na synchronizację Gradle.
4. Wybierz Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Plik będzie w app/build/outputs/apk/debug/app-debug.apk.

ALTERNATYWNIE — AUTOMATYCZNIE:
1. Wgraj zawartość tego folderu do nowego repozytorium GitHub.
2. Otwórz zakładkę Actions.
3. Uruchom workflow „Zbuduj APK Android” (Run workflow).
4. Po zakończeniu pobierz artefakt „Kocie-Glebiny-APK”; w środku będzie app-debug.apk.

Wymagania projektu: Android SDK 35, JDK 17, Gradle 8.9, Android Gradle Plugin 8.7.3.
Minimalna wersja Androida: 6.0 (API 23).
