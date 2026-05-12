# Overleaf HTW Masterarbeit

Dieses Projekt enthält den LaTeX-Code für meine Masterarbeit zum Thema "Menschzentrierte Entwicklung von Interaktionstechniken für webbasierte urbane AR-Partizipationssysteme" an der HTW Berlin, M. Sc. Angewandte Informatik über Overleaf.

**"content/ZZ Latex.tex" enthält Beispiele für alle wichtigen LaTeX Formatierungen.**

## Aufbau

Das Template ist in folgende Ordner geteilt:

- abb: Alle Abbildungen
- anhang: LaTeX-Code und Dateien für den Anhang
- bibliography: BibLaTeX Dateien
- content: Hauptdateien für den eigentlichen Inhalt
- envelope: Alles um den Hauptinhalt herum - Sperrvermerk, Eigenständigkeitserklärung etc.
- settings: Generelle Einstellungen für das Dokument, Wort-Trennung etc.
- main.tex: Hauptdatei für LaTeX

Weitere Infos:
- Die Kapitel sind im "content" Ordner gespeichert. Ähnlich zu BASIC-Programmierung sind diese für die Sortierung mit Zahlen im 10er-Abstand prefixed - hierdurch ist es leichter, spontan neue Kapitel hinzuzufügen.
- In "main.tex:310" werden die einzelnen Kapitel in die Hauptdatei importiert.
- Das Template nutzt die [Zotero to Overleaf Local Sync](https://chromewebstore.google.com/detail/zotero-better-bibtex-to-o/jelihdpmpgnlccliolmmbjgphkhffikl) Chrome Extension, um die Zotero Bibliography zu importieren (bibliography/main.bib).
- Charts habe ich als Mermaid Code in meinem Notion gespeichert. Über "https://notion2overleaf.vantezzen.io/" habe ich dann die Charts als externe Bilder in Overleaf eingebunden - dadurch kann ich die Charts einfach aktualisieren

## Quellen

Das Template baut auf https://github.com/maknesium/latex-vorlage-diplom-bachelor-masterarbeiten/tree/master und https://github.com/tscheffl/HTW-Thesis auf.
