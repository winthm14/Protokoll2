# Protokoll 2
## Übersetzung von C-Programmen  
  
  1. Quelldatei  
  -> preprozessor  
  2. preprozessierter Quellcode  
  -> compiler  
  3. Assembler Quelltext  
  -> Assembler  
  4. object code -> Maschienenbefehl  
  -> Linker
  5. fertiges Programm  
    
Um die übersetzung von C-Programmen zu vereinfachen gibt es Compiler Suiten wie z.B. den Gnu Compiler, Microsoft Visual C/C++.
Weitere nicht so bekannte Compiler Suiten währen z.B. von Borland oder Keil.  
## GNU  
Ein Projekt von Richard Stallmann gegründet mit dem ziel ein unixähnliches Betriebssystem zu schaffen, mit der sicherheit dass der Endbenutzer alle freiheiten hat das Betriebssystem zu kopieren, zu verändern und zu Teilen.  
## GCC  
GCC stand früher für "GNU C Compiler" und war eine Compiler Suite des GNU-Projekts. Da GCC heute aber auch schon ander Programmiersprachen übersetzen kann, steht GCC heute für "GNU Compiler Collection".  

## Die Shell
Die Shell kann man als schnittstelle zwischen Mensch und Maschine sehen. Der Kernel ist der innerste Kern eines Betriebssystems und die Shell ist die "Aussenhülle" eines Betriebssystems und somit die Schnittstelle für den Benutzer.  
Die Shell kann entweder Grafisch als GUI (Graphical User Interface) oder über Komandozeilen als CLI(Comand Line Interface) bedient werden. Je nach Anwendungszweck und Anwender.  


## Arbeiten mit dem Terminal (CLI)  
Das Terminal war früher ein Arbeitsplatz mit Bildschirm und Tastatur, welcher mit einem Großrechner Verbunden war. Dies war damals die einzige möglichkeit auf den Rechnern arbeiten zu können. Meistens wahren mehrere Terminals an einem Großrechner angeschlossen.  
#### Grundlagen:  
1. `<Benutzer>@<Gerätename>:~$` als beispiel -> `thomas@MBPro:~$` diese Zeile ist wichtig um zu wissen mit welchem Benutzer man sich auf welchem Gerät befindet.  Das Dollarzeichen "$" zeigt hierbei an dass man sich als "normaler" Benutzer bewegt und das Tilde(" ~ ")Zeichen zeigt das man sich im Homeverzeichniss befindet. Währe statt dem " ~ "-Zeichen ein "/"(slash), dann währe man im root verzeichniss.  
2. `cd` --> change directory Mit diesem Komando kommt man zurück ins homeverzeichniss. Dies könnte hilfreich sein wenn man nicht mehr weiß wo man sich befindet.
3. `cd ..` Mit disem Komando kommt man um eine Ebene höher.
4. `pwd` --> print working directory Mit diesem Komando kann man das Verzeichnis Ausgeben lassen in dem man sich aktuell befindet.  
5. `ls` --> list Mit disem Komanto kann man alle Dateien und Verzeichnisse (außer ausgeblendete Dateien) im aktuellen verzeichniss anzeigen lassen.  
6. absoluter- und relativer Pfad --> Relativ: man befindet sich z.B. im Homeverzeichniss und möchte nur zum nächsten Unterverzeichniss dann kann man mit einem einfachen `/<nächstes Unterverzeichniss>` ins nächste Unterverzeichniss wächseln.  
Absolut: Man befindet sich in irgendeinem verzeichniss und möchte in ein komplett anderes verzeichniss springen dan benötigt man das Komando `cd /<verzeichnis>/<Unterverzeichnis1>/<Unterverzeichnis2>`  
7. `strg+L`--> zum Löschen des Bildschirms  
8. kurze und lange Optionen: kurze `-<option>` und lange `--<option>`  
9. `which <Programmname>` zum Herausfinden wo im system das programm gespeichert wurde  
10. `type <Komando>` zeigt was dieses Komando bewirkt  
11. `man`--> manual Mit diesem Komando kommt man in das Systemeigene "Handbuch"(die Hilfe im System).  
12. `G`mit der Taste "G" kommt man an den Anfang des Handbuchs.  
13. `shift+G` mit dießer Tastenkombination kommt man ans Ende des Handbuchs.  
14. `/<Suchbegriff>` mit disem Komando kann man im Handbuch nach bestimmten begriffen Suchen.  
15. `Q`mit dieser Taste schließt man das Handbuch.  
16. `echo $0` lässt ausgeben in welcher Shell man sich befindet.
17. `mkdir <Verzeichnissname>` erstellt ein Verzeichniss im Aktuellen verzeichniss.  
18. `rmdir <Verzeichnissname>` löscht das Verzeichniss mit <Verzeichnissname> im Aktuellen verzeichniss.  
