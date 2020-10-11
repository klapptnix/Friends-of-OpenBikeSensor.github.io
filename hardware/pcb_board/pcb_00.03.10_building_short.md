---
layout: default
title: Building Instructions for the PCB v00.03.10
parent: PCB_Board
grand_parent: Hardware
---
# OpenBikeSensor - Folien Bauworkshop

# Bebilderte Kurzanleitung

Inhalt: Bestücken des PCBs v00\.03\.10
<figure>
  <img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short0.jpg" alt="Full Board" class="inline"/>
  <figcaption>Fully equipped PCB v00.03.10</figcaption>
</figure>

<figure>
  <img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short1.jpg" alt="Sensor on Bike" class="inline" />
  <figcaption>Sensor with vertical case mounted on bike</figcaption>
</figure>

# Aufgabe 1: SMDs löten 1/2

1 von 2 Stiftleisten kürzen

Beide auf den ESP32 stecken

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short2.jpg" alt="Alternative Text" class="inline"  />

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short3.jpg" alt="Alternative Text" class="inline"  />

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short4.jpg" alt="Alternative Text" class="inline"  />

Zuerst an den Enden anlöten\, dann die Reihe\, dann ESP32 abnehmen und innen löten

Widerstände R6 und R7 löten: Einen Lötpunkt setzen\, danach mit der Pinzette Widerstand an die Stelle schieben und erhitzen

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short5.jpg" alt="Alternative Text" class="inline"  />

# Aufgabe 2: Widerstände

R1: 10kOhm

R2: 150kOhm

R3: 300kOhm

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short6.jpg" alt="Alternative Text" class="inline"  />

# Aufgabe 3: Spannungsmodule anlöten mit Stiften

Stifte von oben durch Module und Board stecken und von unten anlöten

Oder: mit Stiften auf eine Lötunterlage drücken

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short7.jpg" alt="Alternative Text" class="inline"  />

# Aufgabe 4: GPS und SD-Modul vorbereiten

Gewinkelte Stiftleisteablängen: 4/6pins

Stifte an SD\-Modul löten

GPS noch NICHT löten

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short8.jpg" alt="Alternative Text" class="inline"  />

# Aufgabe 5: Kondensatoren, Diode und Sicherung

C2 und C3: Polung beachten

Diode: Polung beachten

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short9.jpg" alt="Alternative Text" class="inline"  />

# Aufgabe 6: Steckerbuchsen anlöten (Batterie, Schalter, Display)

Von oben stecken\, von unten anlöten

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short10.jpg" alt="Alternative Text" class="inline"  />

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short11.jpg" alt="Alternative Text" class="inline"  />

# Aufgabe 7:  SD+GPS anlöten

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short12.jpg" alt="Alternative Text" class="inline"  />

# Aufgabe 8: Sensorboards vorbereiten

Plastikteil vom Stecker abziehen

Pins vorsichtig nach oben umbiegen

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short13.jpg" alt="Alternative Text" class="inline"  />

# Aufgabe 9: Sensorboards anlöten

Stecken\, Board umdrehen

Gerade anlöten

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short14.jpg" alt="Alternative Text" class="inline"  />

# Aufgabe 10: Displaykabel crimpen

Braun – VCC

Schwarz – GND

Blau – BUT

Weiß – SDA

Grau – SCL

Nur 1\-2mm abisolieren

# Aufgabe 11: Displays mit Knopf löten

# Aufgabe 12: Sensorkabel kürzen und crimpen

<img src="images/OpenBikeSensor_PCB_v00.03.10_Building_short15.jpg" alt="Alternative Text" class="inline"  />

Welche Länge? So lang\, dass das Kabel vom Sensor im Deckel nicht spannt\, wenn beide nebeneinander auf dem Tisch liegen\.

# Aufgabe 13: Display zusammenbauen

Braun – VCC \+ Push Button

Schwarz – GND

Blau – Push Button

Weiß – SDA

Grau – SCL

# Aufgabe 14: Gerät zusammenbauen

Kabel an Akku anlöten\. Polarität beachten, \+ - Pol (rotes Kabel) ist die Seite mit der Rille

Akku mit Kabelbinder am Deckel befestigen

Kabel am Schalter anlöten

Wenn kein vorkonfektioniertes Kabel verwendet wird\, crimpen und Buchse anbringen (Polarität ist egal)