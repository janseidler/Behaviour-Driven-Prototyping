Table of Contents
======

*   [Layout](#layout)
*   [Splitting the Cards Into Abstraction Levels](#splitting-the-cards-into-abstraction-levels)
    *   [Behaviour - Abstract Function](#behaviour-abstract-function)
    *   [Technology - Concrete "Thing"](#technology-concrete-thing)
    *   [Command - User Triggers State/Action/Event](#command-user-triggers-state-action-event)
*   [For Iteration](#for-iteration)
*   [References](#references)

Layout
----------

**Cards size: 7cm x 7cm**


Splitting the Cards Into Abstraction Levels
-------------------------------------------

### Behaviour - Abstract Functions

**Colour: Yellow → [Purchase link](https://www.mercateo.com/p/CIDE4-57981406/Clairefontaine_4217C_Kunstdruckpapier_Kunstpapier_50_Blaetter.html?ViewName=live~secureMode)**

In the abstract cards, "what is to be achieved" should be mapped, e.g. closing, opening, switching on, switching off, saving, deleting, reading, writing, searching, finding, inputting, outputting (displaying?), notifying, moving, measuring, controlling, (...?).

|Behaviour |Icon  |
--- | ---
|Drücken ([png](streamline-icons/behaviours/streamline-icon-finger-tap-1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-finger-tap-1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-finger-tap-1@140x140.png)
|Öffnen ([png](streamline-icons/behaviours/streamline-icon-shipment-open@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-shipment-open@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-shipment-open@140x140.png)
|Schließen ([png](streamline-icons/behaviours/streamline-icon-shipment-package@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-shipment-package@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-shipment-package@140x140.png)
|Anschalten ([png](streamline-icons/behaviours/streamline-icon-flash-1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-flash-1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-flash-1@140x140.png)
|Ausschalten ([png](streamline-icons/behaviours/streamline-icon-flash-off@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-flash-off@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-flash-off@140x140.png)
|Aufhellen ([png](streamline-icons/behaviours/streamline-icon-light-mode-sunny@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-light-mode-sunny@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-light-mode-sunny@140x140.png)
|Abdunkeln ([png](streamline-icons/behaviours/streamline-icon-interface-weather-moon@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-interface-weather-moon@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-interface-weather-moon@140x140.png)
|Passwort eingeben ([png](streamline-icons/behaviours/streamline-icon-password-lock-1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-password-lock-1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-password-lock-1@140x140.png)
|Entsperren ([png](streamline-icons/behaviours/streamline-icon-lock-unlock-1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-lock-unlock-1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-lock-unlock-1@140x140.png)
|Absperren ([png](streamline-icons/behaviours/streamline-icon-lock-2@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-lock-2@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-lock-2@140x140.png)
|Drehen ([png](streamline-icons/behaviours/streamline-icon-road-sign-roundabout@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-road-sign-roundabout@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-road-sign-roundabout@140x140.png)
|Bewegen ([png](streamline-icons/behaviours/streamline-icon-direction-button-arrows@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-direction-button-arrows@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-direction-button-arrows@140x140.png)
|Beschleunigen ([png](streamline-icons/behaviours/streamline-icon-gauge-dashboard-1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-gauge-dashboard-1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-gauge-dashboard-1@140x140.png)
|Bremsen ([png](streamline-icons/behaviours/streamline-icon-navigation-arrows-down@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-navigation-arrows-down@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-navigation-arrows-down@140x140.png)
|Lokalisieren ([png](streamline-icons/behaviours/streamline-icon-location-target@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-location-target@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-location-target@140x140.png)
|Ton ausgeben ([png](streamline-icons/behaviours/streamline-icon-volume-control-full@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-volume-control-full@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-volume-control-full@140x140.png)
|Benachrichtigen ([png](streamline-icons/behaviours/streamline-icon-alarm-bell-check@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-alarm-bell-check@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-alarm-bell-check@140x140.png)
|Erinnern (s. o.) | ![](streamline-icons/behaviours/streamline-icon-alarm-bell-check@140x140.png)
|Temperatur messen ([png](streamline-icons/behaviours/streamline-icon-temperature-thermometer-medium@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-temperature-thermometer-medium@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-temperature-thermometer-medium@140x140.png)
|Bewegung erkennen ([png](streamline-icons/behaviours/streamline-icon-multiple-actions-wifi@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-multiple-actions-wifi@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-multiple-actions-wifi@140x140.png)
|Gesicht erkennen ([png](streamline-icons/behaviours/streamline-icon-face-id-3@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-face-id-3@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-face-id-3@140x140.png)
|Emotion erkennen ([png](streamline-icons/behaviours/streamline-icon-mood-happy@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-mood-happy@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-mood-happy@140x140.png)
|Licht erkennen ([png](streamline-icons/behaviours/streamline-icon-iris-scan-approved-1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-iris-scan-approved-1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-iris-scan-approved-1@140x140.png)
|Herz-Schlag messen ([png](streamline-icons/behaviours/streamline-icon-fitness-heart-rate@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-fitness-heart-rate@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-fitness-heart-rate@140x140.png)
|Zeit erfassen ([png](streamline-icons/behaviours/streamline-icon-time-clock-circle-2@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-time-clock-circle-2@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-time-clock-circle-2@140x140.png)
|Filmen ([png](streamline-icons/behaviours/streamline-icon-controls-camera-record@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-controls-camera-record@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-controls-camera-record@140x140.png)
|Chatten ([png](streamline-icons/behaviours/streamline-icon-conversation-chat-2@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-conversation-chat-2@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-conversation-chat-2@140x140.png)
|Suchen ([png](streamline-icons/behaviours/streamline-icon-search-circle-alternate@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-search-circle-alternate@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-search-circle-alternate@140x140.png)
|Lesen ([png](streamline-icons/behaviours/streamline-icon-read-glasses-1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-read-glasses-1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-read-glasses-1@140x140.png)
|Übersetzen ([png](streamline-icons/behaviours/streamline-icon-translate@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-translate@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-translate@140x140.png)
|Sprechen ([png](streamline-icons/behaviours/streamline-icon-interface-id-face-scan-1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-interface-id-face-scan-1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-interface-id-face-scan-1@140x140.png)
|Hören ([png](streamline-icons/behaviours/streamline-icon-headphones-person@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-headphones-person@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-headphones-person@140x140.png)
|Kommunizieren ([png](streamline-icons/behaviours/streamline-icon-conversation-speak@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-conversation-speak@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-conversation-speak@140x140.png)
|Denken ([png](streamline-icons/behaviours/streamline-icon-brain@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-brain@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-brain@140x140.png)
|Abstand erkennen ([png](streamline-icons/behaviours/streamline-icon-visibility-100@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-visibility-100@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-visibility-100@140x140.png)
|Neigen ([png](streamline-icons/behaviours/streamline-icon-marine-mammal-penguin-slide@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-marine-mammal-penguin-slide@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-marine-mammal-penguin-slide@140x140.png)
|Erschüttern ([png](streamline-icons/behaviours/streamline-icon-electronics-resistor@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-electronics-resistor@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-electronics-resistor@140x140.png)
|Berühren ([png](streamline-icons/behaviours/streamline-icon-touch-finger_1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-touch-finger_1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-touch-finger_1@140x140.png)
|Verbinden ([png](streamline-icons/behaviours/streamline-icon-hyperlink@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-hyperlink@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-hyperlink@140x140.png)
|Steuern ([png](streamline-icons/behaviours/streamline-icon-video-game-xbox-controller@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-video-game-xbox-controller@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-video-game-xbox-controller@140x140.png)
|Fern-Steuern ([png](streamline-icons/behaviours/streamline-icon-drone-controller-1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-drone-controller-1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-drone-controller-1@140x140.png)
|Klingeln ([png](streamline-icons/behaviours/streamline-icon-reception-bell-call@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-reception-bell-call@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-reception-bell-call@140x140.png)
|Speichern ([png](streamline-icons/behaviours/streamline-icon-floppy-disk-2@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-floppy-disk-2@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-floppy-disk-2@140x140.png)
|Herunterladen ([png](streamline-icons/behaviours/streamline-icon-download-thick-bottom@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-download-thick-bottom@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-download-thick-bottom@140x140.png)
|Hochladen ([png](streamline-icons/behaviours/streamline-icon-upload-thick-bottom@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-upload-thick-bottom@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-upload-thick-bottom@140x140.png)
|Aufwärmen ([png](streamline-icons/behaviours/streamline-icon-temperature-thermometer-up@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-temperature-thermometer-up@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-temperature-thermometer-up@140x140.png)
|Abkühlen ([png](streamline-icons/behaviours/streamline-icon-temperature-thermometer-down@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-temperature-thermometer-down@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-temperature-thermometer-down@140x140.png)
|Klopfen ([png](streamline-icons/behaviours/streamline-icon-legal-hammer@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-legal-hammer@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-legal-hammer@140x140.png)
|Bild machen ([png](streamline-icons/behaviours/streamline-icon-filter-picture@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-filter-picture@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-filter-picture@140x140.png)
|Bild bearbeiten (s.o.) | ![](streamline-icons/behaviours/streamline-icon-filter-picture@140x140.png)
|Bild senden (s.o.) | ![](streamline-icons/behaviours/streamline-icon-filter-picture@140x140.png)
|Kontaktieren ([png](streamline-icons/behaviours/streamline-icon-single-neutral-phone-book@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-single-neutral-phone-book@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-single-neutral-phone-book@140x140.png)
|Drucken ([png](streamline-icons/behaviours/streamline-icon-style-three-pin-printer_1@140x140.png), [svg](streamline-icons/behaviours/streamline-icon-style-three-pin-printer_1@140x140.svg)) | ![](streamline-icons/behaviours/streamline-icon-style-three-pin-printer_1@140x140.png)


### Technology - Concrete "Thing"

**Colour: Green → [Purchase link](https://www.mercateo.com/p/648-cla4215c/Farbiges_Papier_A4_120g_Minze_50_Blatt.html?ViewName=live~secureMode)**

Technology/Material: Box, Memory (USB Stick), Chat Bot, Remote Control, Button, Password Field, Camera, Motor, LED, Light Bulb, Switch, Microphone, Computer, Keyboard, Display, GPS, ... + All Sensors

#### Cards

|Technology |Icon  |
--- | ---
|Knopf ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Box ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Glühbirne ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|LED ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Passwort-Feld ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|USB-Stick ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Decodier-Scheibe ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Beacon ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Computer ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Mini-Computer ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Speicher-Karte ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Router ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Dreh-Schalter ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Schalter ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Wand-Schalter ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Kipp-Schalter ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Smart-Phone ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Smart-Watch ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Touch-Screen ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Display ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Maus ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Tastatur ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Positions-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Abstands-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|GPS ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Kamera ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Buzzer ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Lautsprecher ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Mikrofon ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Bewegungs-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Erschütterungs-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Licht-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|UV-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Sound-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Beschleunigungs-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Temperatur-Regler ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Temperatur-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Herz-Schlag-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Kontakt-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Klopf-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|QR-Code ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Karten-Leser ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Übersetzer ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Chat-Bot ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Web-Seite ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Web-Browser ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Such-Maschine ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Gesichts-Scanner ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Emotions-Erkennung ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Motor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Joystick ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Fern-Bedienung ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Sprach-Steuerung ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Musik-Erkennung ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Gyroskop ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Timer ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Neigungs-Sensor ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Drucker ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Aufgaben-Liste ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Kalender ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)
|Maus-Rad ([png](streamline-icons/technologies/), [svg](streamline-icons/technologies/)) | ![](streamline-icons/technologies/)

  
### Command - User Triggers State/Action/Event 
 
**Colour: Red → [Purchase link](https://www.mercateo.com/p/CIDE4-57981359/Clairefontaine_4212C_Kunstdruckpapier_Kunstpapier_50_Blaetter.html?ViewName=live~secureMode)**

An addition for the "behavior cards" shown should be "how exactly should it behave"? e.g. "Move 5cm to the left" is a command the prototyper gives it

|Command |
--- |
|an
|aus
|auf
|zu
|hell
|dunkel
|Sekunde
|Minute
|Stunde
|Tag
|Woche
|Monat
|Jahr
|Stufe
|vorher
|nachher
|90 Grad
|180 Grad
|360 Grad
|links
|rechts
|Click
|unten
|oben
|falsch
|richtig
|Englisch in Deutsch
|Deutsch in Englisch
|mal
|X
|0
|1
|2
|3
|4
|5
|6
|7
|8
|9
|A
|B
|C
|D
|*
|#
|teilweise
|komplett
|wenig
|viel
|Meinen Stand-Ort
|Bestimmter Ort
|Lieblings-Restaurant
|da
|nicht da
|ja
|nein
|Datei
|Foto
|mein
|dein
|unser
|Aufgabe
|Termin
|Geburts-Tag
|Ekel
|Ärger
|Angst
|Traurigkeit
|Freude
|Überraschung
|Verachtung
|(zusätzliche Blanko-Karten)


For Iteration
-------------

* TEST in advance which size of cards really makes sense.
* Unify naming (English vs. German: e.g. Display vs Mouse // Separation vs. Conflation: Speaker vs Touch-Screen //
* Unify icon representation: Flat representation (e.g. timer) vs. outlines (e.g. temperature).
* Separate actions from functions: Enter password vs unlock?
* Separate objects - nouns like "day", "week", "click", "heating" better
* Consider more precisely what is mapped in commands
* Possibly cluster by activity or area (ICF)
* Sharpen separation between smart objects and normal objects
* Possibly icons for commands
* Behaviour cards: "What events can I produce?" (QR-Code or Voice output)
	** Dekodieren, Farbe wechseln, Blinken, Clicken
* Technology cards: "How do I behave?" (QR-Code or Voice output)
* Command cards: "What technologies produce me?", "What technologies consume me?" (QR-Code or Voice output) 


References
----------

*   [https://de.wikipedia.org/wiki/Mikroexpression](https://de.wikipedia.org/wiki/Mikroexpression)
