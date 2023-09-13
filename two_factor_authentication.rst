Zwei-Faktor-Authentifizierung
=============================

Hitobito unterstützt die Zwei-Faktor-Authentifizierung (im Folgenden 2FA) mit folgender Methode:

- Verfahren zur Erzeugung von zeitlich limitierten Einmalkennwörtern «Time-based One-time Password Algorithmus (TOTP)» mittels Authenticator-App und sechsstelligem Code. Dieses ist für alle User:innen von hitobito obligatorisch, welche nicht nur Zugriff auf das eigene Profil haben.

Voraussetzungen
-------------------------------

Für die Zwei-Faktor-Authentifizierung wird ein Smartphone und eine Authenticator-App benötigt. Die Zwei-Faktor-Authentifizierung wurde mit der kostenfreien freeOTP App (https://freeotp.github.io/) entwickelt und getestet, sollte aber grundsätzlich auch mit anderen ähnlichen Apps wie andOTP (https://github.com/andOTP/andOTP) oder Google Authenticator funktionieren.

Einrichten
------------------------------

Um die 2FA einzurichten, muss man in hitobito angemeldet sein. Falls man nicht mehr eingeloggt ist und sich nicht anmelden kann, weil 2FA obligatorisch ist, muss man auf der Anmelde-Seite auf «Passwort vergessen?» klicken und den Instruktionen folgen, um sich via E-Mail einzuloggen. Auf dem eigenen Profil kann man nun im Dropdown „Login“ den Knopf „Zwei Faktor Authentifizierung einrichten“ sehen. Durch Klicken auf diesen Knopf gelangt man auf eine Seite mit einem QR-Code.

In der freeOTP App auf dem Smartphone klickt man nun auf den QR-Code-Knopf in der Kopfzeile. Dadurch öffnet sich die Kamera mit einem Quadrat in der Mitte. Der QR-Code in hitobito kann nun mit der Kamera gescannt werden.

Sobald der Code gescannt wurde, schliesst sich die Kamera und ein neues Element in der Liste sollte auf der App ersichtlich sein. Dies erkennt man anhand der Bezeichnung ''hitobito'' und der E-Mail-Adresse. Durch einen Klick auf den Eintrag wird ein sechsstelliger Code wird angezeigt.

Dieser Code ändert sich alle paar Sekunden. Nun tippt man den Code in hitobito ein und klickt auf „Absenden“. Sollte der Code inkorrekt sein, wird eine entsprechende Nachricht angezeigt und man muss es erneut versuchen. Sobald der Code korrekt und rechtzeitig eingegeben wurde, wird man auf das Profil zurückgeleitet, und die 2FA ist eingerichtet.

Login mit Zwei-Faktor-Authentifizierung
-----------------------------------------------

Sobald die Zwei-Faktor-Authentifizierung eingerichtet ist, muss der Code von der App bei jedem Login eingegeben werden. Nach der Eingabe von E-Mail und Passwort wird man auf eine Seite mit einer Eingabeaufforderung weitergeleitet. Hier tippt man nun wieder den Code aus der freeOTP App ab und klickt auf "Absenden". Sollte der Code nicht korrekt oder bereits abgelaufen sein, wird eine entsprechende Nachricht angezeigt. Ist der Code jedoch korrekt, wird man authentifiziert und in hitobito weitergeleitet.

Zurücksetzen
--------------------------------------

Man kann 2FA auf seinem Profil zurücksetzen. Dort erscheint unter dem Dropdown der Knopf „Zwei Faktor Authentifizierung zurücksetzen“.

Wird die Zwei-Faktor-Authentifizierung zurückgesetzt, wird der Nutzer beim nächsten Login einen neuen QR Code scannen müssen.

Falls der 2FA-Login nicht mehr funktioniert:
1. (Wenn bereits Konto vorhanden) Das Hitobito-Konto in der verwendetet Authentifizierungs-App löschen.
2. Unter https://glp-community.ch „Passwort vergessen?“ unterhalb von „Anmelden“ auswählen.
3. E-Mail-Adresse des Hitobito-Kontos eingeben, danach wird ein Link für das Zurücksetzen des Passworts an die angegebene Adresse verschickt.
4. Sobald das Passwort geändert wurde, ist man wieder eingeloggt. Danach im Dropdown „Login“ die Option „2-Faktor Authentifizierung zurücksetzen“ auswählen.
5. Schritt Nummer 4 wiederholen. Dieses Mal „2-Faktor Authentifizierung einrichten“ auswählen. Nun wird ein QR-Code angezeigt.
6. Installierte Authentifizierungs-App öffnen und damit gemäss obenstehender Anleitung den QR-Code Scannen.
7. Sobald der QR-Code gescannt wurde, sollte ein neues Element mit dem Namen „Hitobito“ in der Liste der App angezeigt werden.
8. Durch einen Klick auf den Eintrag wird ein 6-stelliger Code angezeigt.
9. Den angezeigten Code im Hitobito eintippen. Sobald der Code korrekt und rechtzeitig eingegeben wurde, ist die 2-Fach Authentifizierung wieder eingerichtet.
