# GarminSyncCloud — strona informacyjna OAuth

Publiczna, statyczna witryna opisująca prywatną integrację Garmin Connect, Intervals.icu i Google Drive.

- [Strona główna](https://misiekturner.github.io/)
- [Polityka prywatności](https://misiekturner.github.io/privacy.html)
- [Warunki korzystania](https://misiekturner.github.io/terms.html)

## Publikacja

W repozytorium otwórz **Settings → Pages**. W sekcji **Build and deployment** ustaw:
- **Source:** Deploy from a branch
- **Branch:** main
- **Folder:** /(root)

Kliknij **Save**. Ten krok wymaga uprawnień właściciela repozytorium.

## Google OAuth

W Google Cloud Console → Google Auth Platform → **Elementy marki** wpisz:
- Strona główna: https://misiekturner.github.io/
- Polityka prywatności: https://misiekturner.github.io/privacy.html
- Warunki korzystania: https://misiekturner.github.io/terms.html
- Autoryzowana domena, jeśli potrzebna: misiekturner.github.io

Po zapisaniu przejdź do **Odbiorcy** i opublikuj aplikację, gdy przycisk będzie dostępny.

Ta witryna nie zawiera danych z Garmin, tokenów OAuth, kluczy API ani plików synchronizacji. Repozytorium skryptu pozostaje prywatne.
