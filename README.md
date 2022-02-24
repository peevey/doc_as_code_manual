# Doc as Code-Tutorial

In diesem GIT liegen die Rohdaten des Doc as Code-Tutorials.

## Das Tutorial als PDF und HTML
Das Tutorial als PDF befinden sich unter `exporte`. Wichtig: Im HTML sind die Bildpfade relativ angelegt.

## Kopfdatei

Die Kopfdatei des Tutorials ist [00_tutorial_master.adoc](pages/00_tutorial_master.adoc) 

## Zum Verzeichnisaufbau
Der Aufbau orientiert sich grob an dem bei Verwendung von *Antora* vorgesehenen standardisierten Verzeichnisaufbau. 
https://docs.antora.org/antora/latest/standard-directories/

`assets` enthält die Unterordner `images` und `attachments`. In `images` werden Bilddateien abgelegt, `attachments` ist für weitere Dateitypen vorgesehen, die bspw. zum Download-Zweck in das Dokument eingebettet werden sollen. 

`pages` enthält die einzelnen asciidoc-Textbausteine, aus denen die Dokumentation aufgebaut ist

`examples` enthält die einzelnen asciidoc-Beispieltexte, die im Rahmen des Tutorials verwendet werden

`exporte` enthält einen PDF- und einen HTML-Export des Tutorials

`fonts` enthält die Standardfonts, die im PDF-Export verwendet werden. 

`themes` enthält css-Styles für den HTML-Export und ein PDF-Theme

