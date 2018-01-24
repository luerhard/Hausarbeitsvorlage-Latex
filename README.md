# Hausarbeitsvorlage-Latex
Latex Vorlage für Hausarbeiten. Angepasst auf die Vorgaben des Fachbereich 08 an der Universität Bremen sowie für die deutsche Sprache

## Verwendung

* Literatur in literatur/biobliography.bib hinzufügen.

* Titelblatt in settings/titlepage.tex anpassen.

* Name und Stadt in settings/endofdocument.tex anpassen.

* Bei Bedarf für einen Anhang das Kommentarzeichen (%) in Zeile 8 von settings/endocument.tex entfernen und appendix.tex für den Anhang verwenden.

## Nützliche Befehle
* \enquote{} für im Deutschen übliche Anführungszeichen verwenden. Für Anführungszeichen in Zitaten \enquote*{} benutzen.
  
  
* Zitation:
  * (Autor, Jahr): \parencite{}
  * (Autor, Jahr, S. 123): \parencite\[123\]{} BZW (Autor, Jahr, S. 123 f.): \parencite\[123\psq\]{} BZW für ff. \psqq
  * Autor (Jahr): \textcite{}
  * Autor: \citeauthor{}
  * Jahr: \citeyear{}
   
  * Blockzitate: \begin{quotation} \end{quotation}
   
   
   

## Anmerkungen

* Zitiert wird nach DGPs 2007, der deutschen Version von APA 6.
