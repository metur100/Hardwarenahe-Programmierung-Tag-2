# Hardwarenahe Programmierung Tag 2

 In dieser Ubung behandeln wir Assembler-Grundlagen, die Implementierung von Schleifen in Assembler mithilfe von (bedingten) Sprungen, und nutzen die Prozessor-Flags. Sie werden mit einigen Ihrer Losungen in den nachsten Tagen weiterarbeiten! Sie sollten diese also aufbewahren und so schreiben, dass Sie damit gut weiterarbeiten konnen.


# Aufgabe 1 Teilbarkeit

Schreiben Sie ein Assembler-Programm, das eine ganze Zahl vom Benutzer einliest, dann pruft, ob
diese durch drei teilbar ist, und eine entsprechende Antwort ausgibt.
# Aufgabe 2 Schleifen

Schreiben Sie ein Assembler-Programm, das in einer Schleife alle geraden Zahlen von 1 bis 100 addiert
und das Ergebnis ausgibt.

# Aufgabe 3 Flags
(a) Vervollstandigen Sie das von uns vorgegebene Programm flags02.asm an den markierten Stellen
so, dass der Sprung zum Label error nie ausgefuhrt wird.
(b) Geben Sie eine zweite, alternative Erg¨anzung des Programms an, so dass der Sprung ausgefuhrt
wird.
(c) Formulieren Sie schriftlich (in einer Textdatei): Was bedeutet es fur eine Berechnung mit vor-
zeichenbehafteten Zahlen (signed integer), wenn danach das Carry Flag gesetzt ist?

# Aufgabe 4 Subnetze

(a) Beenden Sie das Assemblerprogramm zu Subnetzen aus der ersten Vorlesung.
• Das Programm muss vom Nutzer eine IP-Adresse abfragen, die durch vier Dezimalzahlen
zwischen 0 und 255 angegeben wird.
• Das Programm gibt fur eine feste Prafixlange (X) zwischen 1 und 32 die Netzwerkadresse
fur die gegebene IP-Adresse aus (die Broadcastadresse brauchen Sie nicht zu bestimmen).
Verwenden Sie zunachst die feste Prafixlange X=12 (Also die Netzwerkmaske 0xFFF00000).
Weitere Informationen finden Sie auf den Vorlesungsfolien. Als Vorlage steht Ihnen ein C Programm in ILIAS zur Verfugung. 
(b) Passen Sie ihr Programm so an, dass auch die Prafixlange (X) vom Benutzer eingegeben wird.
