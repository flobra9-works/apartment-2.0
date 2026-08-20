# B.E@H.O.M.E — Ferienwohnung Gerlinde Brandt

One-Page-Website für die Ferienwohnung in Kalchofen 32, 4850 Timelkam.
Eine einzige HTML-Datei mit eingebettetem CSS und JavaScript. Kein Framework, kein Build-Schritt.

## Starten

Die Seite ist statisch — `index.html` genügt. Lokal ansehen:

```bash
npx serve "Apartment 2.0"
```

Zum Veröffentlichen den kompletten Ordner (`index.html` + `images/` + `media/`) auf den Webspace laden.

## Aufbau

| Datei | Inhalt |
|---|---|
| `index.html` | Komplette Seite: Markup, CSS, JS, Übersetzungen, JSON-LD |
| `images/` | 40 Fotos — 31 Innen- und Außenaufnahmen, Porträt, 7 Landschaftsbilder, 1 Video-Vorschaubild |
| `media/` | `wohnung-wald.mp4` — Videoschleife im Abschnitt *Die Wohnung* |

Sektionen: Hero · Auszeichnungs-Leiste · Fakten · Wohnung · *Zitat Khayyam* · Das bietet dir die Unterkunft · Galerie · Region · *Zitat „Hinter dem Horizont"* · Jahreszeiten *(mit Stifter-Zitat)* · Gästestimmen · Gastgeberin *(mit Busch-Zitat)* · Preise & Buchung · FAQ · Kontakt.

## Noch offen

**1. Preis** — In `index.html` nach `XX&nbsp;€` suchen. Airbnb zeigt den Nächtigungspreis nur nach Eingabe eines Zeitraums an, deshalb konnte er nicht übernommen werden.

**2. Impressum und Datenschutz** — Im Footer stehen zwei Links auf `#`. Ziele eintragen.

Alles andere ist mit echten Inhalten befüllt.

## Auszeichnungen auf der Startseite

Direkt im Hero steht der **Gäste-Favorit-Block** im Stil von Airbnb: Lorbeer, 4,98, fünf Sterne und 56 Bewertungen. Für Screenreader liegt daneben ein unsichtbarer Satz, der dieselbe Aussage in Worten wiedergibt.

Gleich darunter folgt eine Leiste mit sechs Merkmalen: **Blitzsauber · Gäste-Favorit & Superhost · 2 Schlafzimmer · bis 5 Gäste · Balkon & Garten · Eigener Eingang.**

> **Eine Abweichung:** Im dritten Screenshot stand „5,0 ★ · 44 Bewertungen". Airbnb selbst gibt im Inserat und in den strukturierten Daten **4,98 aus 56 Bewertungen** an; die 44 ist dort die Zahl der Bewertungen, die *Gastfreundschaft* erwähnen. Die Seite verwendet durchgehend die belegten Werte 4,98 und 56.

## Das bietet dir die Unterkunft

Die Sektion zeigt zuerst zehn Highlights als Karten, darunter alle **51 Ausstattungsmerkmale** als kleine Chips, in acht Gruppen: Ausblick (2) · Bad (5) · Schlafen & Wäsche (9) · Für Familien (2) · Küche & Essen (17) · Außenbereich & Zugang (8) · Komfort & Sicherheit (5) · Services (3).

Die Liste stammt 1:1 aus dem Airbnb-Dialog „Das bietet dir diese Unterkunft" (56 Einträge, davon 5 als nicht verfügbar markiert → 51 vorhandene). Abschließend nennt eine Zeile, was **nicht** vorhanden ist: Klimaanlage, Wäschetrockner, Kohlenmonoxidmelder und Außenkameras.

> **Zwei Widersprüche im Airbnb-Inserat, bitte prüfen:**
> 1. Der Beschreibungstext nennt einen **Ultra-HD Smart TV**, in der Merkmalsliste ist **HDTV aber als „nicht verfügbar" markiert**. Die Seite folgt der Beschreibung und führt den TV unter den Highlights. Vermutlich ist auf Airbnb nur das Häkchen nicht gesetzt.
> 2. Die Merkmalsliste sagt **„Gemeinsam genutzter Garten"**, Beschreibung und Fotos sprechen vom **eigenen Gartenbereich**. Die Chips geben Airbnbs Formulierung wieder („Garten, nicht komplett umzäunt"), der Fließtext Ihre.

## Woher die Inhalte stammen

Alle Angaben wurden aus dem [Airbnb-Inserat](https://www.airbnb.at/rooms/47439814) und von [gerlinde-brandt.at](https://gerlinde-brandt.at) übernommen und gegeneinander geprüft.

**Aus dem Airbnb-Inserat:** 5 Gäste · 2 Schlafzimmer · 3 Betten · 1,5 Bäder · Kingsize-Doppelbett und Babybett im ersten Schlafzimmer · Boxspringbett 140 cm im zweiten · Ultra-HD Smart TV · Wasserkocher, Toaster und Plattengrill · Tee und Kaffeepads fürs Frühstück · Bettwäsche und Bügeleisen · Check-in 16:00–24:00 per Schlüsselbox, Check-out bis 11:00 · Ortstaxe 2,40 € pro Person und Nacht in bar, nicht unter 15 Jahren · Treppensteigen erforderlich · kostenlose Parkplätze entlang des Hauses.

**Bewertung:** 4,98 von 5 aus 56 Bewertungen, davon 98 % mit fünf Sternen. Einzelwerte: Sauberkeit 5,0 · Genauigkeit 5,0 · Check-in 5,0 · Kommunikation 5,0 · Lage 4,8 · Preis-Leistung 5,0. Ausgezeichnet als Gäste-Favorit und Superhost, seit fünf Jahren Gastgeberin, Antwortrate 100 %.

**Gästestimmen:** Vier echte Bewertungen von Luka, Susanne, Jana und Jens, sinnwahrend gekürzt. Die Monatsangaben sind aus den relativen Zeitangaben („vor 3 Tagen", „vor 2 Wochen") abgeleitet und daher **ungefähr — bitte gegenprüfen.** Wenn Sie andere Bewertungen bevorzugen, stehen alle 56 in Ihrem Airbnb-Konto; ersetzt werden sie unter den Schlüsseln `voi.q1`–`voi.q4` und `voi.c1`–`voi.c4`, jeweils auch im englischen `T.en`-Objekt.

## Die Zitate

| Zitat | Urheber | Wo | Quelle |
|---|---|---|---|
| „Das Leben ist eine Reise — und wer reist, lebt zweimal." | Omar Khayyam (1048–1131) | Band nach *Die Wohnung* | alte Ferienwohnungs-Seite |
| „Hinter dem Horizont geht es weiter!" | Gerlinde Brandt | Band nach *Region* | gerlinde-brandt.at |
| „Die Berge stehen noch, die Sonne strahlt auf sie herunter, und die Jahre sind dahin als wie ein Tag." | Adalbert Stifter (1805–1868) | *Jahreszeiten* | oberösterreichischer Dichter, gemeinfrei |
| „Viel zu spät begreifen viele die versäumten Lebensziele …" (vollständig) | Wilhelm Busch | *Gastgeberin* | alte Ferienwohnungs-Seite |

**Nicht übernommen:** Von gerlinde-brandt.at stammen außerdem Zitate von Blaise Pascal („Das Herz kennt Gründe …") und Albert Einstein („Logic will get you from A to B …") sowie ihr Leitsatz „Habe den Mut, deinen eigenen Weg zu gehen …". Diese gehören inhaltlich zur Coaching-Praxis, nicht zur Ferienwohnung, und würden die Seite überfrachten — auf Wunsch aber leicht ergänzbar.

## Über die Gastgeberin

Der Text kombiniert drei Quellen: ihren Werdegang von gerlinde-brandt.at (Wechsel aus dem Banken- und Versicherungswesen, seit 2008 als Beraterin und Coach in Timelkam), ihre eigene Vorstellung aus dem Airbnb-Profil (als Zitat vorangestellt) und die Geschichte der ausgezogenen Kinder.

> **Zur Prüfung:** „Nach Jahren im Banken- und Versicherungswesen" ist bewusst unbestimmt formuliert, weil die Quelle keine Dauer nennt. Falls eine konkrete Zahl bekannt ist, wird der Satz dadurch stärker.

## Galerie

Die Sektion zeigt zwölf Aufnahmen als Vorschau; ein Klick öffnet sie einzeln in einer Lightbox (Pfeiltasten, Escape).

Der Button **„Alle 31 Bilder ansehen"** — im Hero und unter der Vorschau — öffnet eine eigene Vollansicht mit allen 31 Aufnahmen samt Beschreibung. Diese Ansicht wird beim ersten Öffnen aus dem `PHOTOS`-Array im JavaScript aufgebaut; Bildunterschriften und Alt-Texte stehen dort zweisprachig und folgen dem Sprachumschalter.

**Ein Bild ergänzen oder tauschen:** Datei in `images/` legen und im `PHOTOS`-Array eine Zeile nach dem Muster `['datei.jpg', breite, höhe, 'Beschreibung DE', 'Description EN']` eintragen. Die Zahl im Button-Text (`gal.all` in beiden Sprachen) mit anpassen.

## Das Video im Abschnitt „Die Wohnung"

Statt eines Fotos läuft dort eine stumme Videoschleife (Farne im Sonnenlicht, 17 s, 1920 × 1080).

- Es spielt **nur, solange es im Bild ist**, und pausiert beim Wegscrollen — Dekodieren im Hintergrund kostet sonst grundlos Akku.
- Bei `prefers-reduced-motion` startet es **gar nicht** von selbst und bekommt stattdessen Bedienelemente.
- `preload="metadata"` lädt nur den Dateikopf; daraus zeigt der Browser das erste Bild, ohne die ganze Datei zu holen.

> **Zur Dateigröße:** Das Video wiegt **21 MB** — mehr als alle 39 Fotos zusammen (14 MB). Wer bis zu diesem Abschnitt scrollt, lädt es vollständig. Da kein ffmpeg verfügbar war, konnte ich es nicht verkleinern. Eine auf ~3–5 MB komprimierte Fassung (etwa 1280 px breit, CRF 28) oder ein auf 6–8 Sekunden gekürzter Ausschnitt würde die Seite spürbar leichter machen — die Datei einfach unter gleichem Namen in `media/` ersetzen.

**Der `moov`-Block wurde nach vorne verschoben.** In der Originaldatei lag er am Ende, wodurch der Browser erst alle 21 MB hätte laden müssen, bevor das erste Bild erscheint. Beim Umschreiben mussten alle 22 Chunk-Offsets in der `stco`-Tabelle um den Versatz korrigiert werden; geprüft ist, dass sie sämtlich im gültigen Datenbereich liegen.

**Lizenz:** Das Video stammt von Artlist (Jakub Klawikowski). Artlist verlangt in der Regel keine Namensnennung auf der Seite — anders als das CC-lizenzierte Titelbild. Bitte prüfen Sie, dass Ihre Artlist-Lizenz die Nutzung auf einer gewerblichen Website abdeckt.

## Der Film über die Region

Am Ende von *Region & Ausflugsziele* steht eine Reisereportage der Deutschen Welle über das Salzkammergut und Hallstatt ([gT1cWGtuA7I](https://www.youtube.com/watch?v=gT1cWGtuA7I)).

**Eingebunden als Klick-Vorschau, nicht als normaler YouTube-Code.** Ein gewöhnlicher Einbettungscode lädt schon beim Seitenaufruf Skripte von Google und setzt Cookies — auch bei Besuchern, die das Video nie starten. Stattdessen liegt ein lokal gespeichertes Vorschaubild (`images/salzkammergut-video-vorschau.jpg`) mit Abspiel-Button in der Seite; erst beim Klick wird der Player nachgeladen, und zwar über `youtube-nocookie.com`.

Geprüft: Vor dem Klick geht **keine einzige Anfrage** an YouTube, ytimg oder Google. Ebenfalls geprüft über die Player-Konfiguration: `playableInEmbed: true` — DW erlaubt die Einbettung.

> Wird das Video getauscht, genügt es, `data-video` am Button zu ändern und ein neues Vorschaubild zu hinterlegen. Das passende Bild liegt jeweils unter `https://i.ytimg.com/vi/<VIDEO-ID>/maxresdefault.jpg`.

## Bewegung auf der Seite

| Wo | Was |
|---|---|
| Beim Laden | Das Panorama fährt langsam aus einer Nahaufnahme zurück, darüber staffeln sich Eyebrow, Überschrift, Text, Bewertung und Buttons ein |
| Hero beim Scrollen | Das Foto zieht langsamer mit als der Text darüber |
| Ganz oben | Fortschrittsbalken über die Seitenlänge |
| Sektionen | Karten und Bilder schweben gestaffelt ein, Fotos und Video aus leichtem Zoom |
| Die Wohnung | Videoschleife, spielt nur im sichtbaren Bereich |
| Zitat-Bänder | Das Hintergrundfoto driftet gegenläufig |
| Fakten-Leiste | Die Zahlen zählen beim Einscrollen hoch |
| Galerie | Bilder zoomen beim Überfahren, Bildunterschrift blendet ein |
| Navigation | Aktiver Punkt folgt der Scroll-Position |
| Hintergrund | Aurora-Flächen treiben dauerhaft in langsamen Schleifen |

Alles respektiert `prefers-reduced-motion`.

## Der schwebende Buttonblock

Rechts unten liegt ein fixiertes Feld mit **„Anfrage senden"** und **„Auf Airbnb prüfen"** — ausschließlich die beiden Buchungsaktionen. Es erscheint nach dem Hero und tritt in der Sektion *Preise & Buchung* zurück, wo dieselben Aktionen bereits im Seiteninhalt stehen. Auf schmalen Bildschirmen sitzt es über der Navigationsleiste.

Der Galerie-Button ist **nicht** Teil davon: Er steht fest im Hero und unter der Galerie-Vorschau.

## Zweisprachigkeit

Deutsch steht im Markup und ist die Vorgabe, Englisch im JavaScript-Objekt `T.en`. Beim Laden nimmt die Seite einen Schnappschuss des deutschen Markups, dadurch ist das Umschalten verlustfrei. Die Wahl wird im `localStorage` gemerkt; Besucher mit nicht-deutscher Browsersprache landen automatisch auf Englisch.

**Neuen Text ergänzen:** Element mit `data-i18n="mein.schluessel"` auszeichnen und denselben Schlüssel in `T.en` eintragen. Enthält der Text Markup, stattdessen `data-i18n-html` verwenden.

> Ein Element mit `data-i18n` darf kein Markup und keine weiteren `data-i18n`-Elemente enthalten — beim Umschalten wird sein Textinhalt ersetzt und verschachtelte Kinder gingen verloren. Für solche Fälle `data-i18n-html` nehmen.

## Fotos und Lizenzen

**Innenaufnahmen und Porträt** stammen von Gerlinde Brandt — keine Namensnennung nötig.

**Landschaftsaufnahmen** kommen von Wikimedia Commons und sind frei verwendbar, **solange die Namensnennung erhalten bleibt**. Die Credits stehen unter den Bildern und im Footer.

| Datei | Motiv | Urheber | Lizenz |
|---|---|---|---|
| `hero-attersee-panorama.jpg` | Attersee vom Kleinen Schoberstein | Tigerente | CC BY-SA 4.0 |
| `region-hoellengebirge.jpg` | Attersee mit Höllengebirge | Tigerente | CC BY-SA 4.0 |
| `region-salzkammergut.jpg` | Salzkammergut-Landschaft | Pimlico27 | CC BY-SA 4.0 |
| `jahreszeit-fruehling.jpg` | Blütenstaub auf dem Attersee | Tigerente | CC BY-SA 4.0 |
| `jahreszeit-sommer.jpg` | Segeln am Attersee | Tigerente | CC BY-SA 4.0 |
| `jahreszeit-herbst.jpg` | Herbstblick vom Schafberg | Josef Lahmer | CC BY-SA 3.0 |
| `jahreszeit-winter.jpg` | Höllengebirge im Winter | Stefankasberger | CC BY-SA 4.0 |

**Hinweis zum Porträt:** `gastgeberin.jpg` liegt nur in 350 × 450 px vor. Für den Kreis (270 px) reicht das, auf hochauflösenden Displays wirkt es aber leicht weich. Eine größere Fassung wäre eine spürbare Verbesserung.

**Weitere Fotos:** In `Downloads/Airbnb_Fotos` liegen 39 Aufnahmen; 31 davon sind eingebunden. Ausgelassen wurden nur nahezu identische Doppelungen.

## Technische Hinweise

- **Buchung** verlinkt auf das Airbnb-Inserat (Zimmer 47439814). Ein eingebetteter Kalender ist nicht möglich: Airbnb erlaubt kein Einbetten per iframe.
- **Anfrageformular** öffnet das E-Mail-Programm mit vorbereiteter Nachricht an `info@gerlinde-brandt.at`. Kein Server, keine Datenübertragung an Dritte.
- **Karte** ist Google Maps (`google.com/maps?q=…&output=embed`), ohne API-Schlüssel. Google setzt dabei eigene Cookies und lädt Ressourcen von seinen Servern — anders als die zuvor verwendete OpenStreetMap-Karte ist das **nicht mehr datensparsam.** Wer das vermeiden möchte, kann jederzeit zurück auf OpenStreetMap wechseln (siehe Git-Historie).
- **Absicherung:** Meldet ein System keine Frames zurück, blendet ein Fallback nach zwei Sekunden alle Inhalte ein — die Seite bleibt nie leer.
- **Datensparsam bis auf die Karte:** Die Seite selbst setzt keine Cookies und lädt keine Analytics. Externe Verbindungen sind Google Fonts und die Google-Maps-Karte im Footer. Der Regions-Film lädt erst auf Klick.

### Fünf Fallstricke, die hier bewusst umgangen sind

- **Der `display`-Wert der Dialoge hängt an `[open]`.** Ein geschlossenes `<dialog>` versteckt der Browser über seinen eigenen Stylesheet — aber *jede* Autoren-Regel für `display` überstimmt das, unabhängig von der Spezifität, weil Autoren-Stile grundsätzlich vor Browser-Stilen gewinnen. Ein schlichtes `.lightbox{display:grid}` legt die geschlossene Lightbox deshalb formatfüllend über die ganze Seite.

- **Der Scroll-Lock der Dialoge hängt nicht am `close`-Ereignis.** In manchen Engines wird es nie ausgeliefert; ein verpasstes Entsperren würde die ganze Seite unscrollbar hinterlassen. Stattdessen räumt `closeDialog()` auf jedem Schließweg auf, zusätzlich fängt ein Escape-Handler auf Dokumentebene ab.
- **`backdrop-filter` steht auf `.topbar::before`, nicht auf `.topbar`.** Ein Element mit `backdrop-filter` wird zum Bezugsrahmen für seine `position:fixed`-Kinder — sonst springt die mobile Navigation vom unteren Rand in den Kopfbereich.
- **Die Hero-Eyebrow ist weiß, nicht türkis.** Über einem Foto verträgt die hellere Schrift fast die doppelte Hintergrundhelligkeit bei gleichem Kontrastverhältnis. Dadurch bleibt das Panorama offen, statt für ein kleines Label abgedunkelt zu werden.
- **Der Freiraum für die mobile Navigationsleiste steht im Footer, nicht in `main`** — und *nach* der `padding-block`-Kurzschreibweise, sonst gewinnt diese über die Quellreihenfolge.

## Geprüft

Beide Dialoge beim Laden `display:none`, unter dem Seitenmittelpunkt liegt die Überschrift · 51 Ausstattungs-Chips in 8 Gruppen · 7 Fakten-Kacheln und 9 Distanz-Karten, keine überlappt beim Umbruch · kein horizontales Scrollen von 375 px bis 1920 px · Hero-Text erfüllt WCAG AA über dem aufgehellten Foto an neun geprüften Fensterbreiten und -höhen, inklusive der Media-Query-Grenze bei 900 px (schlechtester Wert 4,27 → nachgeschärft auf 5,18) · alle Bedienelemente mindestens 44 px, auch die vergrößerte Marke überlappt die Navigation nicht · genau eine `h1` · alle Bilder mit Alt-Text und festen Maßen, 31 der Vollgalerie lazy geladen · Sprachwechsel über 260 Schlüssel verlustfrei, Galerie-Beschriftungen und Alt-Texte inbegriffen · Lightbox inklusive Umlauf · Vollgalerie öffnet aus Hero und Galerie, schließt per Button und Escape und gibt den Scroll jeweils frei · Dock-Sichtbarkeit und Fortschrittsbalken an fünf Scroll-Positionen · Google-Maps-Karte lädt und löst die Adresse korrekt auf · Video spielt, läuft in Schleife, ist stumm und hält das Seitenverhältnis 4∶5 auf Desktop und Mobil · Regions-Film lädt vor dem Klick nichts von Google und setzt danach den nocookie-Player ein · JSON-LD gültig, inklusive Bewertung.
