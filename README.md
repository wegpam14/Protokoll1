# Protokol1
## Thema: Einführung zur Verwendung von GitHub

Name: Patrick Wegl  
KNr.: 16
Klasse: 4AHME  
Gruppe: 3  

Anwesend: Sarah Vezonik,Alois Vollmaier,Patrick Wegl,Mercedes Wesonig,Matthias Winter,Thomas Winter  
Abwesend: ----

## Was versteht man unter Git bzw. GitHub?
##### Git ist eine Software zur versionsverwaltenden Dateiablage, welche kostenlos zur Verfügung gestellt wird.

##### Entscheidende Merkmale dieses Systems sind:  
* Es kann an verschiedenen Zweigen (Branches) des Dateisystems zur selben Zeit gearbeitet werden, dass ermöglicht Veränderungen an einem bereits von Nutzern verwendeten Programms, da nur auf einem parallel verlaufendem Zweig gearbeitet wird, während der vom Endnutzer verwendete Zweig unberührt bleibt. Sobald die einwandfreie Funktion des veränderten Programms sichergestellt wird, können die Zweige wieder verschmolzen werden. 
* Da kein zentraler Server verwendet wird, sondern jeder eine lokale Kopie des gesamten Repositorys besitzt, ist keine dauerhafte Internetverbindung erforderlich. Nach Änderungen kann man sein Repository mit der Onlineversion abgleichen. Sollten mehrere Personen zur selben Zeit die selbe Datei verändert haben, kommt es zu einem Konflikt, welcher gelöst werden muss.

##### GitHub bezeichnet eine auf Git basierende Software, welches als OpenSource-Projekt gehandhabt wird und dadurch jedem ermöglicht, jedes Repository einzusehen.
* Man kann dem Verfasser eines Repositorys nur für sich selbst zu nutzen, kann man eine kostenpflichtige Version erwerben.
##### GitHub ermöglicht Projekte im Team einfach abzuwickeln, da jederzeit von jedem nachvollzogen werden kann, wer, was, wann verändert hat und das Wiederherstellen von alten Versionen jederzeit möglich ist.

## Verwaltungsebenen:
##### Die Unterteilung des Git-Systems erfolgt in fünf Ebenen:
* Stash  
* Workspace  
* index  
* lokal repository  
* remote repository  

##### Befehle:
* **git checkout:** _Dateien werden vom lokal repository in den Workspace bewegt._
* **git add:** _Dateien werden vom Workspace nach Index bewegt._
* **git commit:** _Dateien werden vom Index ins lokal repository bewegt._
* **git push:** _Dateien vom lokal repository auf Git-Server geladen._
* **git clone:** _Das gesamte Repository wird geklont._
* **git pull:** _Dateien werden vom Git-Server heruntergeladen._
* **git status:** _Alle Änderungen anzeigen._
* ...

## Branch:

Ein Branch bezeichnet einen Zweig innerhalb eines Repositorys. Die Idee hinter Verzweigungen ist die, eine funktionsfähige, stabile Version welche bereits von einem Kunden genutzt wird nicht zu gefährden und trotzdem weiterarbeiten zu können. Beim erstellen eines neuen Repositorys wird standartmäsig ein Master Branch erstell. In diesem Zweig sollte sich immer eine funktionsfähige Version befinden. Die Nebenzweige werden genutzt um weiterzuarbeiten bzw. neue Dinge auszuprobieren. Wenn der Nebenzweig stabil läuft und man diese Version in den Hauptzweig integrieren will, kann man beide verschmelzen.
Weitere Informationen sind [hier](https://guides.github.com/introduction/flow/) zu finden.

##Issue:
Issue bedeutet "_Vorschläge_", diese werden verwendet um den Entwicklern eines Repositorys über Fehler oder verbesserungsvorschläge zu informieren. Der Adressat eines Issues wird, kann über eine e-Mail informiert werden.

## Markdown:

Damit kann man Text-Dateien mit einfachen Mitteln in eine formatierte HTML-Datei verwandeln. Markdown wird unter anderem von GitHub verwendet.  
Beispiele für Regeln zur Formatierung  
* "#","##", und "###" für Überschriften
* "* ... *": *italic*
* **...** ": **fett**
* "[Name]""(Link)": erstellt einen Link  
Weitere Informationen finden Sie [hier](https://guides.github.com/)
