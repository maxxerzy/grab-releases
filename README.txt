grab! — holt aus einer Adresse oder Datei so viel wie möglich heraus

INSTALLATION
1. grab! auf den Ordner „Programme“ ziehen.

2. grab! aus „Programme“ öffnen (Doppelklick). macOS meldet „grab!“ nicht geöffnet:
   Die App kann nicht auf Schadsoftware geprüft werden, weil grab! nicht von Apple
   notarisiert ist. Auf „Fertig“ klicken (nicht „In den Papierkorb legen“).

3. Einmal erlauben („Dennoch öffnen“):
   a. Systemeinstellungen öffnen (Apple-Menü > Systemeinstellungen …).
   b. In der Seitenleiste auf „Datenschutz & Sicherheit“ klicken.
   c. Ganz nach unten zum Abschnitt „Sicherheit“ scrollen. Dort steht
      „grab!“ wurde blockiert, um deinen Mac zu schützen.
   d. Daneben auf „Dennoch öffnen“ klicken.
   e. Mit Passwort oder Touch ID bestätigen. Fragt macOS noch einmal nach, erneut
      „Dennoch öffnen“ wählen.
   Das ist nur einmal nötig. (Rechtsklick > Öffnen umgeht das ab macOS 15 nicht mehr.)
   Kein „Dennoch öffnen“ zu sehen? grab! zuerst noch einmal öffnen (Schritt 2) und
   dann erneut nachsehen — der Knopf erscheint nur direkt nach einem blockierten Versuch.

4. grab! sitzt danach oben rechts in der Menüleiste (Pfeil nach unten im Kreis), ohne Dock-Symbol und
   ohne Fenster. Ein Klick auf das Symbol öffnet das Feld: Adresse einfügen und holen,
   oder eine Datei oder einen Ordner auf das Symbol ziehen. macOS fragt, ob grab!
   Mitteilungen zeigen darf — so meldet es fertige Läufe.

WAS GEHT OHNE WEITERES
Webseiten, Videos und Ton, Bilder, PDFs, Archive, Transkription auf dem
Mac, Suche über alles Geholte, Konvertieren von Video, Ton und Bild. ffmpeg bringt
grab! selbst mit. Für die Transkription lädt grab! beim ersten Mal ein Sprachmodell.

WAS MEHR BRAUCHT (alles über Homebrew, https://brew.sh)
   brew install deno          YouTube zuverlässig, mit Untertiteln
   brew install tesseract tesseract-lang   Text in Bildern und gescannten PDFs
   brew install pandoc        Word, OpenDocument, EPUB lesen und konvertieren
   brew install ffmpeg        Konvertieren nach WebM und Opus, Videos im Format AV1
Was auf deinem Mac da ist und was fehlt, zeigt grab! unter „Was geht“.

BROWSER-ERWEITERUNG
Ein Knopf im Browser: diese Seite mit grab! holen. Die Anleitung für Chrome, Firefox
und Safari steht in grab! unter Einstellungen (Zahnrad) > Browser > Anleitung.

Benötigt macOS 15 oder neuer und einen Mac mit Apple-Chip (M1 oder neuer).
Updates holt grab! selbst. Datenschutz & Bedingungen: grab! arbeitet auf deinem Mac;
ins Netz geht es zu den Adressen, die du holen lässt, zu GitHub wegen Updates und zu
Hugging Face für Sprachmodelle.
Volltext in grab! > Einstellungen > Über > Datenschutz & Bedingungen.

—

grab! — gets as much as possible out of an address or a file

INSTALL
1. Drag grab! onto the Applications folder.

2. Open grab! from Applications (double-click). macOS says "grab!" Not Opened:
   it can't check the app for malicious software, because grab! isn't notarized by
   Apple. Click "Done" (not "Move to Trash").

3. Allow it once ("Open Anyway"):
   a. Open System Settings (Apple menu > System Settings…).
   b. Click "Privacy & Security" in the sidebar.
   c. Scroll all the way down to the "Security" section. There it says
      "grab!" was blocked to protect your Mac.
   d. Click "Open Anyway" next to it.
   e. Confirm with your password or Touch ID. If macOS asks once more, click
      "Open Anyway" again.
   You only need to do this once. (Right-click > Open no longer skips this on
   macOS 15 and later.) No "Open Anyway" button? Open grab! once more first
   (step 2), then look again — it only appears right after a blocked attempt.

4. grab! then lives at the top right of the menu bar (a down arrow in a circle), with no Dock icon
   and no window. Click the icon to open the field: paste an address and fetch it, or
   drag a file or folder onto the icon. macOS asks whether grab! may show
   notifications — that is how it reports finished runs.

WORKS OUT OF THE BOX
Web pages, video and audio, images, PDFs, archives, transcription on
your Mac, search across everything fetched, converting video, audio and images.
grab! brings its own ffmpeg. For transcription it downloads a speech model once.

NEEDS MORE (all via Homebrew, https://brew.sh)
   brew install deno          YouTube reliably, with subtitles
   brew install tesseract tesseract-lang   text in images and scanned PDFs
   brew install pandoc        read and convert Word, OpenDocument, EPUB
   brew install ffmpeg        converting to WebM and Opus, videos in AV1 format
grab! shows what is there and what is missing on your Mac under "Was geht".

BROWSER EXTENSION
One button in the browser: fetch this page with grab!. Instructions for Chrome,
Firefox and Safari are in grab! under Settings (gear) > Browser > Anleitung.

Requires macOS 15 or later and a Mac with Apple silicon (M1 or newer). The interface
is in German. grab! updates itself. Privacy & terms: grab! works on your Mac; it goes
online to the addresses you ask it to fetch, to GitHub for updates and to Hugging
Face for speech models. Full text in
grab! > Einstellungen > Über > Datenschutz & Bedingungen.
