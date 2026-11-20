# Project OS einrichten

Project OS hilft dir, dein Projekt zu entwickeln, Aufgaben anzulegen und Wissen zu sammeln. Du arbeitest in einem ChatGPT-Projekt. Deine Projektdateien liegen in einem privaten Repository auf GitHub, einem Online-Ordner, der die gespeicherten Änderungen festhält.

## 1. GitHub-Konto erstellen

1. Öffne die [GitHub-Registrierung](https://github.com/signup) und erstelle ein kostenloses Konto.
2. Bestätige deine E-Mail-Adresse über die Nachricht von GitHub. Falls die Nachricht fehlt, prüfe den Spam-Ordner oder lass sie dir erneut zusenden.
3. Verwende ein eigenes, starkes Passwort und aktiviere die Zwei-Faktor-Authentifizierung in GitHub. Gib Passwörter, Zugriffstokens und Wiederherstellungscodes niemals an ChatGPT weiter. [GitHub-Hilfe zum Kontostart](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)

## 2. Ein privates Repository erstellen

1. Melde dich bei GitHub an und öffne [Neues Repository](https://github.com/new).
2. Gib unter **Repository name** einen Namen ein, etwa `mein-projekt`, und wähle **Private**.
3. Aktiviere **Add README** und klicke auf **Create repository**. Die README, eine kurze Einführungsdatei, erzeugt den ersten gespeicherten Repositoryzustand, den Project OS für die Einrichtung braucht.
4. Prüfe, dass auf der neuen Repositoryseite **Private** und `README.md` angezeigt werden. Kopiere die Adresse aus der Adressleiste. Sie enthält deinen GitHub-Namen und den Repository-Namen. [GitHub-Hilfe zur Repository-Erstellung](https://docs.github.com/en/get-started/start-your-journey/creating-a-repository-for-your-project-on-github)

## 3. GitHub mit ChatGPT verbinden

1. Öffne in ChatGPT **Einstellungen** und dann **Apps** oder **Plugins**. Wähle die GitHub-Anbindung deiner Beta-Umgebung und starte die Verbindung.
2. Melde dich auf der angezeigten GitHub-Seite an und erlaube den Zugriff auf dein Projekt-Repository. Fehlt es in der Auswahl, prüfe in den Repository-Einstellungen der GitHub-Anbindung, ob du mit dem richtigen GitHub-Konto angemeldet bist und das Repository ausgewählt und freigegeben ist.
3. Fürs Speichern verwendet die Beta eine GitHub-Anbindung mit Schreibzugriff. Die gewöhnliche GitHub-App in ChatGPT bietet Lesezugriff. Meldet der Assistent fehlenden Schreibzugriff, prüfe die Freigabe für dein Repository und wende dich bei Bedarf an die Person, die dir den Beta-Zugang bereitgestellt hat. [ChatGPT-Hilfe zur GitHub-Verbindung](https://help.openai.com/en/articles/11145903-connecting-github-to-chatgpt)

## 4. Ein ChatGPT-Projekt erstellen

1. Klicke in der Seitenleiste von ChatGPT auf **Neues Projekt** und gib deinem Projekt einen Namen.
2. Öffne das Projekt und starte darin einen Chat. Du erkennst das geöffnete Projekt an seinem Namen. [ChatGPT-Hilfe zu Projekten](https://help.openai.com/en/articles/10169521-projects-in-chatgpt)

## 5. Project OS starten

1. Öffne die öffentliche [Startdatei START-PROJECT-OS.md](START-PROJECT-OS.md) und klicke in der GitHub-Dateiansicht auf **Download raw file**, um sie herunterzuladen. Du benötigst dafür keinen Zugriff auf das private Entwicklungsrepository.
2. Lade die Datei einmal im Projektchat hoch und schreibe „Richte Project OS für mein Projekt ein.“ Füge den Link zu deinem Repository hinzu.
3. Beantworte die Fragen zu Projektname, Zweck und gewünschten Funktionen. Falls mehrere Branches zur Auswahl stehen, wähle den Branch für dein Projekt. Ein Branch ist eine Entwicklungslinie im Repository. Bei einem neuen Repository heißt die Hauptlinie meist `main`.

## 6. Den Einrichtungsvorschlag freigeben

1. Prüfe die Zusammenfassung. Sie zeigt dein Repository, den Branch, den geprüften Ausgangsstand, die gewählten Funktionen und die Orte, an denen Project OS speichern darf. Der Ausgangsstand ist durch einen Commit gekennzeichnet, also eine gespeicherte Version auf GitHub.
2. Prüfe den vollständigen Änderungsvorschlag, auch Patch genannt. Er gilt für zwei Dateien direkt im Repository. `PROJECT-OS.md` enthält deine Projektkonfiguration und die Regeln. `PROJECT-OS-CHANGES.md` hält fest, welche Änderungen du freigegeben hast. Beide Dateien werden gemeinsam in einem Commit gespeichert.
3. Gib genau diesen Vorschlag für das angegebene Repository, den Branch und den geprüften Ausgangscommit ausdrücklich frei. Bestätige, dass nur dieser Chat die Einrichtung speichern darf. Solange er speichert, darf weder ein zweiter Chat noch eine andere Person Änderungen in diesem Repository veröffentlichen. Das ist die Single-Writer-Regel.
4. Warte auf die Bestätigung mit der Commit-Kennung und den aktivierten Funktionen. Der Assistent meldet Erfolg, sobald er die Speicherung durch erneutes Lesen auf GitHub geprüft hat. Hat sich der Ausgangsstand geändert, prüfe und bestätige einen neuen Vorschlag. Ist das Speicherergebnis unklar, warte auf die Prüfung des Assistenten, bevor du erneut speicherst.

## 7. Die Projektanweisung einfügen

1. Kopiere nach der bestätigten Einrichtung den ausgefüllten Anweisungstext aus der Antwort. Er enthält dein Repository und deinen Branch.
2. Öffne im ChatGPT-Projekt das Menü **⋯** und wähle **Projekteinstellungen**. Füge den Text in die **Projektanweisungen** ein und speichere ihn.
3. Öffne bei Bedarf die Projekteinstellungen erneut und prüfe, ob der Text gespeichert ist. [ChatGPT-Hilfe zu Projektanweisungen](https://help.openai.com/en/articles/10169521-projects-in-chatgpt)

## 8. Eine Funktion ausprobieren

1. **Projektentwicklung** – „Schlage eine kurze Projektbeschreibung für meine README vor und zeige mir den Patch.“ Wenn die README zum vereinbarten Schreibbereich gehört und der Vorschlag passt, gib genau diesen Patch zum Speichern frei.
2. **Aufgabenpilot** – „Lege die Aufgabe ‚Ideen für das erste Projekttreffen sammeln‘ an.“ Die Aufgabe wird im Repository erfasst.
3. **Wissenssammlung (Commonplace Book)** – „Speichere die folgende eigene Notiz unter ‚Projekttreffen‘. Beim nächsten Treffen sammeln wir zuerst offene Fragen.“ Die Notiz wird in der vereinbarten Wissensablage gespeichert.

Wähle ein Beispiel für eine aktivierte Funktion. Du kannst beim Einrichtungschat bleiben oder in einem neuen Chat desselben Projekts ausprobieren, ob Project OS die gespeicherten Daten wiederfindet.
