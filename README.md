# weltanschauung_app

## Zweck

Öffentliche Seiten des Store-Büros von nga unter weltanschauung.app, etwa die Datenschutzerklärungen der Apps.

## Benutzung

GitHub Pages veröffentlicht den Zweig `main` unter `https://weltanschauung.app`, die Domain steht in `CNAME`.

| Pfad | Inhalt |
| --- | --- |
| `index.html` | Startseite mit Links zu den Apps |
| `dozenal/privacy.<sprache>.html` | Datenschutzerklärung von Dozenal Calc in 14 Sprachen |

Die Adressen stehen so in den Stores. Wer einen Pfad ändert, ändert auch die Store-Einträge. Die Seiten von Dozenal
Calc kommen aus `legal/` von `ens_dozenal_calc` und werden dort gepflegt, hier nur kopiert.

Lokal ansehen: `index.html` im Browser öffnen.

## Entwicklung

- Prüfbefehl: `pre-commit run --all-files`
- Tests: `pre-commit run --all-files --hook-stage pre-push`
