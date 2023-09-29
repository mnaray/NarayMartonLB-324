# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.

1. Im ersten Schritt muss man pre-commit mit `pip` installieren:
   ```
   pip install pre-commit
   ```
2. Im nächsten Schritt geht es darum, ein Script in .git/hooks/ zu erstellen:
   ```
   pre-commit install
   ```
3. Zuletzt kann getestet werden, ob alles lauft:
   ```
   pre-commit run -a --hook-stage commit # formatieren
   pre-commit run -a --hook-stage push # testen
   ```

## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.