# IQB Testprofil

ID of profile-store: `ptest`

Creator: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

2 Profile definiert:

## Profil "Testprofil - Aufgabe"

ID of profile: [https://w3id.org/iqb/p99/unit/](https://w3id.org/iqb/p99/unit/)

### Stimulus

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Entwickler:in | Text | Einzeilig, Sprache(n): de   | iqb_author |
| Klassenstufe | [Vokabular](http://w3id.org/openeduhub/vocabs/educationalLevel/) | url: '[http://w3id.org/openeduhub/vocabs/educationalLevel/](http://w3id.org/openeduhub/vocabs/educationalLevel/)', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | iqb_educational_level |
| Test Vokabular In-Form One Aufgabenbereiche | [Vokabular](https://w3id.org/iqb/v53/n1/) | url: '[https://w3id.org/iqb/v53/n1/](https://w3id.org/iqb/v53/n1/)', Einmalauswahl, Zeige nur erste Ebene, integrierte Darstellung, Nummerierung unterdrückt | q5 |
| Test Vokabular In_form Multiple Art der Quelle | [Vokabular](https://w3id.org/iqb/v28/aq/) | url: '[https://w3id.org/iqb/v28/aq/](https://w3id.org/iqb/v28/aq/)', Mehrfachauswahl, Zeige nur erste Ebene, integrierte Darstellung | q6 |
| Schulform | [Vokabular](https://w3id.org/kim/schularten/) | url: '[https://w3id.org/kim/schularten/](https://w3id.org/kim/schularten/)', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | iqb_school_type |
| Für SPF geeignet | Ja/Nein | Text für WAHR: ja, Text für FALSCH: nein | iqb_spf |
| hilfsmittelfrei | Ja/Nein | Text für WAHR: ja, Text für FALSCH: nein | iqb_unassisted |
| Kopfhörereinsatz | [Vokabular](https://w3id.org/iqb/v24/kh/) | url: '[https://w3id.org/iqb/v24/kh/](https://w3id.org/iqb/v24/kh/)', Mehrfachauswahl, integrierte Darstellung, Nummerierung unterdrückt | iqb_phones |
| Leitidee | [Vokabular](https://w3id.org/iqb/v51/im/) | url: '[https://w3id.org/iqb/v51/im/](https://w3id.org/iqb/v51/im/)', Einmalauswahl, Zeige nur erste Ebene, Dialogbox, Nummerierung unterdrückt | iqb_competence |
| Stimuluszeit | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_stimulus |
| Aufgabenzeit | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_unit |
| Quellenangaben | Text | Mehrzeilig, Sprache(n): de   | iqb_copyright |
| Notizfeld | Text | Mehrzeilig, Sprache(n): de   | iqb_note_field |
| Unverträgliche Aufgaben | Text | Einzeilig, Sprache(n): de   | iqb_compatibility |

### Hörsequenz/Video

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Anzahl Vorspielen | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein | iqb_time_play |
| Transkript | Text | Mehrzeilig, Sprache(n): de   | iqb_transcript |

## Profil "Testprofil - Item"

ID of profile: [https://w3id.org/iqb/p99/item/](https://w3id.org/iqb/p99/item/)

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Freitext Item A | Text | Einzeilig, Sprache(n): de   | w2 |
| Boolean Item | Ja/Nein | Text für WAHR: störend, Text für FALSCH: nicht relevant | w3 |
| Number Item | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | w4 |
| Test Vokabular In-Form Aufgabenbereiche | [Vokabular](https://w3id.org/iqb/v53/n1/) | url: '[https://w3id.org/iqb/v53/n1/](https://w3id.org/iqb/v53/n1/)', Einmalauswahl, Zeige nur erste Ebene, integrierte Darstellung, Nummerierung unterdrückt | w5 |
| Test Vokabular Dialog  Art der Quelle | [Vokabular](https://w3id.org/iqb/v28/aq/) | url: '[https://w3id.org/iqb/v28/aq/](https://w3id.org/iqb/v28/aq/)', Mehrfachauswahl, Zeige nur erste Ebene, integrierte Darstellung | w6 |

