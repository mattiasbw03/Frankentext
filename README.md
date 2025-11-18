FrankenText — Generering af tekst med Markov-kæde
Denne opgave går ud på at skrive et C-program, der kan generere tilfældige sætninger ud fra bogen Frankenstein af Mary Shelley. Programmet analyserer teksten og bygger en simpel Markov-kæde, hvor hvert ord (kaldet et token) gemmes sammen med information om, hvilke ord der kan følge efter det.
Først renses hele bogteksten for ikke-printbare tegn, så der ikke opstår fejl i tokeniseringen. Derefter opdeles teksten i tokens (ord), og et såkaldt successor-table opbygges. Dette tabelsystem holder styr på, hvilke ord der typisk følger efter hinanden i teksten.
Når tabellen er opbygget, kan programmet generere nye sætninger ved at:
Vælge et tilfældigt ord, der starter med stort begyndelsesbogstav.

Tilføje efterfølgende ord ved tilfældigt valg blandt de registrerede efterfølgere.

Stoppe, når et ord ender på ., ? eller !.

Programmet udskriver herefter to genererede sætninger: én, der ender på spørgsmålstegn, og én, der ender på udråbstegn.
Opgaven træner forståelsen af:
Strenghåndtering og tokenisering i C

Brug af arrays og pointere

Arbejde med datastrukturer (Markov-kæder)

Randomisering og generering af tekst

Til afleveringen skulle der implementeres de funktioner, der var markeret med // YOUR CODE HERE, samt vedlægges eksempeloutput og et flowchart, der illustrerer programmets arbejdsgang.
