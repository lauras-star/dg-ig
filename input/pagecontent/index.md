<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

Eine Hausarztpraxis erfasst und übermittelt Arzneimittelallergien von Patient:innen mithilfe
von HL7 FHIR. Die Daten (Allergien gem. SNOMED CT-Codes etc.) werden anschliessend mit einer
Notfallstation geteilt.

### Scope

Dieses IG definiert die standardisierte Dokumentation & den Austausch von Arzneimittelallergien auf Basis von CH Core. Es umfasst u.a. klinischer Status, Kritikalität, Beginn der Allergie. Ausgeschlossen sind andere Allergiearten (bspw. Lebensmittel), sowie Diagnose & Behandlung.


### Artefakte

TODO: Ergänzt pro Artefakt einen Satz, wofür es da ist.

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Dieses Profil definiert die Anforderungen zur strukturierten Erfassung von Arzneimittelallergien und ermöglicht einen standardisierten Datenaustausch zwischen Hausarztpraxis und Notfallstation.
* [Penicillinallergie bei Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Zeigt konkretes Beispiel einer Penicillinallergie.

<!-- TODO_Name ist der Name hinter "Instance:" in beispiele.fsh,
     z. B. AllergyIntolerance-PenicillinAllergieAnna.html -->

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Laura Milicevic

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
