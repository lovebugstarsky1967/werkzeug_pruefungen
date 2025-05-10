# Werkzeug- & Equipment-Prüfungs-App (ETMA Π)

## Inhaltsverzeichnis
- [Über die App](#über-die-app)
- [Aktuelle Version verwenden](#aktuelle-version-verwenden)
  - [App starten](#app-starten)
  - [Wichtiger Hinweis zur Datenspeicherung](#wichtiger-hinweis-zur-datenspeicherung)
- [Hauptfunktionen](#hauptfunktionen)
  - [Navigation](#navigation)
  - [Dashboard](#dashboard)
  - [Ausrüstung](#ausrüstung)
  - [Inspektionen](#inspektionen)
  - [Kalender](#kalender)
  - [Berichte](#berichte)
  - [Einstellungen (Datenverwaltung)](#einstellungen-datenverwaltung)
- [Zukünftige Entwicklung: Appwrite-Integration](#zukünftige-entwicklung-appwrite-integration)
- [Beitragen](#beitragen)

## Über die App

ETMA Π (Equipment Testing Management Application) ist eine Web-Anwendung zur Verwaltung von Prüfterminen für ortsveränderliche Werkzeuge und Equipment. Sie ermöglicht das Erfassen von Geräten, das Planen und Protokollieren von Inspektionen sowie die Übersicht über anstehende und überfällige Prüfungen.

Diese Version ist eine reine Frontend-Anwendung, die im Browser läuft.

## Aktuelle Version verwenden

### App starten

1. **Code herunterladen/speichern**: Stellen Sie sicher, dass Sie den vollständigen HTML-Code der Anwendung (bereitgestellt als werkzeug_web_app_dashboard_v1 oder ähnlich) auf Ihrem Computer haben.
2. **Als HTML-Datei speichern**:
   - Öffnen Sie einen Texteditor (z.B. Notepad, VS Code, Sublime Text).
   - Fügen Sie den gesamten HTML-Code ein.
   - Speichern Sie die Datei mit der Endung .html (z.B. etma_app.html).
3. **Im Browser öffnen**:
   - Navigieren Sie im Datei-Explorer zu dem Ordner, in dem Sie die .html-Datei gespeichert haben.
   - Doppelklicken Sie auf die Datei. Sie wird sich in Ihrem Standard-Webbrowser öffnen.

### Wichtiger Hinweis zur Datenspeicherung

In der aktuellen Version werden alle Daten (hinzugefügte Geräte, Inspektionen etc.) nur temporär im Arbeitsspeicher des Browsers gehalten. Das bedeutet:

- **Wenn Sie den Browser-Tab schließen oder die Seite neu laden, gehen alle nicht exportierten Daten verloren!**
- Nutzen Sie die Funktionen unter "Einstellungen", um Ihre Daten manuell als CSV- oder JSON-Backup-Datei auf Ihrem Computer zu sichern und bei Bedarf wieder zu laden.