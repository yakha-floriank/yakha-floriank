# Git für Beginner
- GitHub einrichten:

Mit dem Code `git config` werden grundelegende Dinge eingerichtet, wie z.B mit `--global user.name ""`wird ein Name angelegt, mit `--global user.email""` die dazugehörige EMail. In Windows das Ende einer Zeile wird mit \r (Carriage Return) und \n (Line Feed) gekenzeichnet,bei macOS/Linux hingegen nur mit \n. Damit da keine Probleme auftreten werden wir hier für Windows `git config --global core.autocrlf true`bei macOS anstatt `true`, `input`

Hilfe und eine Liste mit den allgemeinen Commands: 
`git config --help`

 kurze Übersicht:
 `git config -h`
 
 -erstellen von Ordner : `mkdir name`
Um zwischen verschiedenen Verzeichnissen zu wechseln: `cd name`

-erstellen von Git Repository mit `git init` mit `ls -a` können alle Dateien darin angezeigt werden
Zum löschen des Git Repository `rm -rf .git`



- Git Workflow


Project directory(PD) --> Git Repository (GR )über die Staging Area (SA) 
Die Staging Area ist eine Art zwischenschritt vor der Git Repository

`git add filename` um diese in die SA zu befördern. Ist alles ok, geht die datei mit `git commit -m "Kommentar XY"` in GR

Wird eine Datei aus dem PD entfernt, verbleibt sie jedoch zunächst in der SA. Mit `git add filename` wird diese aus SA gelöscht. Immer an `git commit -m ""`denken.

Erstellen von Text in Dateien `echo hello > file1.txt`

Mit `git status` wird der aktuelle status der PD und SA abgerufen.
Um eine Gruppe von Dateien zu in Die SA zu schieben `git add *.txt`
mit `git add .` wird das komplette PD inzugefügt. 

Löschen von Dateien:
`rm filename.txt`
`git rm filename.txt`

Dateien verschieben/ Umbenennen:
`mv filename.txt ordnername`

Dateien ignorieren:  `.gitignore`






  








