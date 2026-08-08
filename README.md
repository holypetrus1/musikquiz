# Musikquiz Blind-Player

Ein privates Musik-Zeitstrahlspiel mit 300 Karten für den Zeitraum 1970–2015.

Die Karten enthalten eigene QR-Codes. Diese werden **innerhalb der Web-App** gescannt. Die App sucht den hinterlegten Song über die Spotify Web API und startet die Wiedergabe, ohne Titel, Interpret oder Jahr anzuzeigen. Erst über **„Lösung anzeigen“** werden die Kartendaten aufgedeckt.

## Einmalige Spotify-Einrichtung

1. Unter <https://developer.spotify.com/dashboard> eine Spotify Developer App erstellen.
2. In deren Einstellungen als Redirect URI exakt die URL dieser GitHub-Pages-Seite hinterlegen:
   `https://holypetrus1.github.io/musikquiz/`
3. Die Client-ID der Spotify App kopieren.
4. Die Musikquiz-Seite öffnen, Client-ID eintragen und mit Spotify verbinden.

Für die Wiedergabe ist Spotify Premium erforderlich. Die App verwendet OAuth mit PKCE; es gibt kein Client Secret im Repository. Die Client-ID und OAuth-Tokens werden nur lokal im Browser gespeichert.

## Spielen

1. Spotify auf dem Handy öffnen und sicherstellen, dass ein Wiedergabegerät aktiv ist.
2. Musikquiz-Web-App öffnen und „Kamera starten“ wählen.
3. QR-Code einer Karte scannen.
4. Der Song startet, ohne dass die Lösung angezeigt wird.
5. Gemeinsam raten und anschließend „Lösung anzeigen“ drücken.

## Druckdateien

Die Vorderseiten und QR-Rückseiten sind für 12 Karten pro DIN-A4-Seite ausgelegt. Die QR-Rückseiten sind horizontal gespiegelt, damit Vorder- und Rückseite beim Duplexdruck deckungsgleich liegen. Beim Drucken 100 % / „Tatsächliche Größe“ verwenden.

Nur für den privaten Gebrauch. HITSTER ist eine Marke des jeweiligen Rechteinhabers; dieses Projekt ist eine unabhängige Eigenentwicklung und nicht mit HITSTER oder Jumbo verbunden.
