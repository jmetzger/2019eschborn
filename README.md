# SLES 11 / Linux Training 

## Bash Cheatsheet 
https://appletree.or.kr/quick_reference_cards/Unix-Linux/Linux%20Command%20Line%20Cheat%20Sheet.pdf

## VI Cheatsheet 
http://www.atmos.albany.edu/daes/atmclasses/atm350/vi_cheat_sheet.pdf

## Purpose of lost+found - folder 
https://unix.stackexchange.com/questions/18154/what-is-the-purpose-of-the-lostfound-folder-in-linux-and-unix

## Little Exercise (german)

```
1. In den home ordner von root wechseln 
2. Ordner uebung erstellen
3. In den Ordner wechseln 
4. Ordner Montag erstellen
5. In den Ordner wechseln
6. Leere datei Ablauf.txt erstellen. 
7. Ein Verzeichnis höher wechseln
8. Ordner "Montag" löschen 
9. In halt der /var/log/messages in die Datei ausgabe.txt umleiten.
10.Verzeichnis "archiv" erstellen
11.Datei ausgabe.txt in Ordner archiv kopieren. 
12.Letzte 20 Zeilen der Datei /etc/services in die Datei auszug.txt 
13.Erste 20 Zeilen der Datei /etc/services in die Datei auszug.txt anhängen 
14.Alle Zeilen in der das Wort "tcp" in /etc/services vorkommt in die Datei asuzug.txt anhängen.
```

## Wichtige Befehle ##

```
# Verzeichnis löschen mit Inhalt 
rm -R verzeichnisnahme
# leere Datei anlegen 
touch meindatei 
# Datei in Ordner kopieren (Ordner muss existieren !) 
cp /etc/services /root/meinordner/
# Inhalt einer Datei ausgeben
cat /pfad/zur/datei 
# z.B. 
cat /etc/services 



```
