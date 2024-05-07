Anweisungen:

1. Verwende die bereitgestellte HTML-Datei als Ausgangspunkt für deine Übung.

2. Erstelle eine CSS-Datei, benenne sie styles.css und verlinke sie mit deinem HTML-Dokument.
3. Allgemeine Seitenformatierung:

   - Setze die Hintergrundfarbe des Body auf #9f9f9f.
   - Verwende eine geeignete Schriftart für die gesamte Seite. Du kannst Verdana, Geneva, Tahoma oder eine serifenlose Schriftart verwenden.
   - Entferne den Innenabstand (padding) und die Aussenabstand (margin) des Body, indem du beides auf 0 setzt.

**Prüfe:** ob keine Abstände vorhanden sind, schreibe dafür ein Wort in den Body und schaue ob es an den Rändern "klebt". Der Hintergrund sollte die gesamte Seite ausfüllen, in grau sein und die Schriftart sollte überall gleich sein.

4. Styling des main-Elements:

   - Style den Hauptcontainer wie folgt (verwende das HTML-Element main):
     - Zeige den Inhalt als Spalte an (display flex) mit der Eigenschaft flex-direction (Flexbox).
     - Füge einen Abstand (padding) von 12px hinzu, um Platz um den Inhalt zu schaffen.

5. Text-Styling:

   - Erstelle CSS-Regeln für Textelemente mit verschiedenen Klassen:
     - **.title:**
       - Style mit einer Schriftgröße (font-size) von 120px und einer fettgedruckten Schrift (bold). Stelle sicher, dass kein Abstand (margin) vorhanden ist, indem du ihn auf 0 setzt.
     - **.paragraph:** Setze die Textfarbe (color) auf #000000.
     - **.paragraph.dark-mode:** ändere die Textfarbe (color) für diesen Kombinationsselektorauf #eeeeee.
     - **.text-size-small:** Setze die Schriftgröße (font-size) auf 16px.
     - **.text-size-medium:** Setze die Schriftgröße (font-size) auf 24px.
     - **.text-size-large:** Setze die Schriftgröße (font-size) auf 36px.

6. Styling Layout-Container:

   - Erstelle die Klasse **.container** und definiere die folgenden Eigenschaften:
     - Zeige die Unterelemente (children) in einer Reihe an (verwende flex-direction/Flexbox).
     - Zentriere den Inhalt horizontal (space-between).
     - Füge einen Abstand (padding) von 12px zwischen den Unterlementen (children) hinzu.
     - Setze eine Höhe (height) von 300px.
     - Mache ihn vollständig in der Breite (width) 100%.
     - Füge einen Abstand (padding) von 12px nach unten (bottom) hinzu.

7. Box-Styling:

   - Style **.box-Elemente** wie folgt:
     - Verwende box-sizing, um sicherzustellen, dass das der Innenabstand (padding) die Gesamtbreite und -höhe des Elements nicht beeinflusst (border-box).
     - Setze die Höhe (height) und Breite (width) auf 100%.
     - Füge ein Innenabstand (padding) von 12px hinzu.
     - Setze die Hintergrundfarbe (background-color) auf #00ffbf.
     - Erstelle einen Kombinationsselektor .box h2, um h2-Elemente innerhalb von .box-Elementen zu stylen, und setze den Innenabstand (padding) auf 0.

8. Hintergrundfarben-Klasse:

   - Erstelle eine Klasse .bg-red, die die Hintergrundfarbe (background-color) auf #ff0000 setzt.

9. Erstelle eindeutige IDs für Box 1 und Box 2. Die beiden Boxen sollten bis auf die Hintergrundfarbe identisch sein:

   - Styling für #box-1:
     - Verwende box-sizing, um anzugeben, dass das Padding (Abstand) in die Gesamtbreite und -höhe des Elements einbezogen werden soll (border-box).
     - Setze die Höhe (height) und Breite (width) von #box-1 auf 100%, sodass es die gesamte Höhe und Breite seines übergeordneten Elements einnimmt.
     - Füge ein Padding von 12px hinzu, um Platz im Inneren des Elements zu schaffen.
     - Setze die Textfarbe (color) auf #eeeeee (hellgrau).
     - Setze die Hintergrundfarbe (background-color) auf #0d2927 (ein dunkles Teal oder Blaugrün).
   - Styling für #box-2:
     - Kopiere das Styling von #box-1 und wende es auf #box-2 an.
     - Ändere die Hintergrundfarbe auf #515e78 (eine gedämpfte blaugraue Farbe).

10. Styling der Überschriften:

    - Style alle h2-Elemente auf der Seite:
    - Entferne den Abstand, indem du ihn auf 0 setzt.
      - Setze die Schriftgröße (font-size) auf 32px.

11. Transformations-Effekte:

    - Erstelle eine Klasse .transform-width mit den folgenden Eigenschaften:
      - Setze eine Mindestbreite (min-width) von 600px.
      - Füge einen Übergangseffekt für die Mindestbreite (min-width 0,5s ease-in-out) hinzu.
      - Erstelle eine Kombinationsklasse .transform-width:hover mit den folgenden Eigenschaften:
        - Verwende die :hover-Pseudoklasse, um die Mindestbreite (min-width) beim Hover auf 1200px zu erhöhen und füge einen Zeiger-Cursor hinzu.

12. Animations-Effekte:

    - Definiere Animations-Keyframes für die folgenden Klassen:

      - Erstelle eine Klasse .animate-text-color:

        - Füge der Klasse die Textfarbe (color) #fff hinzu und den Animationsnamen color mit einer Dauer von 1s linear infinite.
        - Erstelle eine Animation (@keyframe) namens color, die die Textfarbe überblendet:
          - Setze die Textfarbe bei 0% auf #eeeeee (hellgrau).
          - Setze die Textfarbe bei 50% auf #000000 (schwarz).
          - Setze die Textfarbe bei 100% auf #eeeeee (hellgrau).

      - Erstelle eine Klasse .animate-rotate:

        - Füge der Klasse den Animationsnamen rotate mit einer Dauer von 5s linear infinite hinzu.
        - Füge der Klasse transform-origin: center hinzu.
        - Erstelle eine Animation (@keyframe) namens rotate für die Rotation:
          - Setze eine Rotation (transform rotate) von 0deg bei 0%.
          - Setze eine Rotation von 180deg bei 50%.
          - Setze eine Rotation von 360deg bei 100%.

      - Erstelle eine Klasse .animate-wiggle:

        - Füge der Klasse den Animationsnamen wiggle mit einer Dauer von 1s ease-in-out infinite hinzu.
        - Erstelle eine Animation (@keyframe) namens wiggle für einen Wackeleffekt:
          - Setze eine verschiebung (transform translateX) von 12px bei 0%.
          - Setze eine verschiebung von -12px bei 50%.
          - Setze eine verschiebung von 12px bei 100%.

      - Erstelle eine Kombinationsklasse .animate-shake:hover:
        - Füge der Klasse einen Zeiger (cursor pointer) hinzu.
        - Füge den Animationsnamen shake mit einer Dauer von 0,25s ease-in-out infinite hinzu.
        - Erstelle eine Animation (@keyframe) namens shake, die beim Hover einen Schüttel-Effekt auslöst:
          - Setze eine verschiebung (transform translateX) von 9px, 3px bei 0%.
          - Setze eine verschiebung von -9px, -3px bei 50%.
          - Setze eine verschiebung von 9px, 3px bei 100%.
      - Erstelle eine Klasse .animate-mix:
        - Füge der Klasse transform-origin: center hinzu.
        - Füge sowohl die Animationen color als auch wiggle, durch Komma getrennt, zur Klasse hinzu.
        - color hat eine Dauer von 1s linear infinite.
        - wiggle hat eine Dauer von 5s linear infinite.

13. Testen und Anpassen:

    - Teste deine Webseite, um sicherzustellen, dass sie wie beabsichtigt angezeigt wird.
    - Du kannst den Inhalt nach Belieben anpassen und deine eigene Kreativität einbringen, während du dich an die gegebenen Richtlinien hältst.
      Versuche, die Übung abzuschließen, ohne den finalen CSS-Code anzusehen. Sobald du die Übung abgeschlossen hast, kannst du deine Lösung mit dem finalen CSS-Code vergleichen, um zu sehen, wie gut du den gewünschten Stil und die Animationen umgesetzt hast.
