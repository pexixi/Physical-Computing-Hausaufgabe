# Physical Computing Hausaufgabe

Hier das Repo zu meiner Hausaufgabe im Seminar Physical Computing bei Peter Ehses.

##### Jannis Steinhauer | Sommersemester 21 | Intermedia Design

<br>

## About

Ziel dieses Projektes ist es, mit Hilfe des Mikrocontrollers _Arduino Uno_, einen LED-Streifen über ein Potentiometer zu steuern.
Dieser LED-Streifen durchleuchtet das ganze Hue-Farbspektrum, die Geschwindkeit des Leuchtens kann durch den Drehregler des Potentiometers gesteuert werden.

![PROJEKT-SHOWCASE](https://i.imgur.com/faGwydJ.jpg)
![PROJEKT-SCHALTUNG](https://i.imgur.com/CtsT45u.jpg)<br>
##### Beispielvideo
[![VIDEO](https://img.youtube.com/vi/t_hAx9NmS8o/0.jpg)](https://www.youtube.com/watch?v=t_hAx9NmS8o)

<br>

## Step 1

### Komponenten

##### Folgende Komponenten werden für das Projekt benötigt:

* 1x Arduino Uno
* 1x Breadboard
* 1x Potentiometer
* 1x LED-Streifen
* 8x Kabel

### Software

##### Folgende Software wird im Projekt genutzt:

* PlattformIO IDE
* Arduino-Libary
* FastLED-Libary


<br>

## Step 2

### Schaltplan

##### Der Schaltplan hat folgendes Layout:

![_Schaltplan in Tinkercad_](https://i.imgur.com/YrBSaw2.png)

<br>

## Step 3

### Code

##### In diesem Repository befinden sich alle benötigten Dateien um den Code-Teil des Projektes zu realisieren.

[Download Code als zip-Datei](https://github.com/pexixi/Physical-Computing-Hausaufgabe/archive/refs/heads/master.zip)

_Sidenotes_: 
* Alle Dateien des Repositories müssen in einem Ordner lokal gespeichert werden, die Dateistruktur darf nicht verändert werden.
* Nutzen Sie einen Code-Editor wie beispielsweise [Visual Studio Code](https://code.visualstudio.com/) (VSC) um den Code zu editieren.
* Nutzen Sie die IDE von PlattformIO, welche in VSC installiert werden kann (Plugin), um den Code auf den Arduino zu hochzuladen.
* Sollten Sie Probleme beim Einrichten von PlattformIO in VSC haben, schauen Sie in die [Dokumentation](https://docs.platformio.org/en/latest/integration/ide/vscode.html).
* **Die einzige Datei die verändert werden sollte ist die _main.cpp_ im _src_ - Ordner**

### Install Software

* Schritt 1: Wenn Sie die IDE von PlattformIO benutzen, starten Sie ein neues Projekt und wählen Sie ihren Microcontroller aus
* Schritt 2: Installieren Sie  die Libary FastLED von PlattformIO in ihr Projekt
* Schritt 3: Kopieren Sie die Dateien aus dem Repo in den Projektordner
* Schritt 4: Bearbeiten Sie die main.cpp-Datei nach Ihrem belieben
* Schritt 5: [Builden Sie das Projekt](https://docs.platformio.org/en/latest/core/quickstart.html#process-project)
* Schritt 6: [Laden Sie das Projekt auf den Arduino](https://docs.platformio.org/en/latest/core/quickstart.html#process-project)

<br>

## Step 4

### Finish

##### Kompilieren/Builden Sie das Projekt in VSC und laden Sie es anschließend auf das Arduino hoch.

<br>
