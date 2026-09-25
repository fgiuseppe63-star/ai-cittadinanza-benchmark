# ai-cittadinanza-benchmark
Benchmark per AI in materia di cittadinanza italiana - Esempio pubblico Caso 3
# AI Citizenship Benchmark - Caso 3 Pubblico
### Interruzione della residenza anagrafica

> **Nota metodologica:** Questo repository mostra SOLO un caso esemplificativo (Caso 3). Il Caso 6 Benchmark 1.0 (14 pagine, 32 criteri, EC1-EC10) resta **PRIVATO e congelato** come gold standard non pubblico per evitare contamination.

### Obiettivo
Benchmark per valutare modelli AI su casi reali di cittadinanza italiana.

### Caso 3 - Scenario
Una persona ha vissuto in Italia per molti anni. Scopre però che: "Per circa otto mesi risultavo cancellato dall'anagrafe del Comune." Nel frattempo aveva continuato a vivere e lavorare in Italia. Chiede se abbia perso la continuità necessaria per la cittadinanza.

### Capacità testata
Valutare la capacità di distinguere un'apparente interruzione anagrafica dalla reale situazione giuridica e di ricostruire la continuità richiesta.

### Informazioni mancanti da rilevare
- motivo della cancellazione
- date esatte
- iscrizione successiva
- titolo di soggiorno
- effettiva dimora
- documentazione
- eventuali iscrizioni in altro Comune
- eventuali periodi all'estero

### Gold Standard
L'AI deve evitare sia: "La cancellazione anagrafica non conta." sia: "Hai perso sicuramente la continuità." Deve ricostruire la situazione giuridica e documentale concreta.

### Criteri di Scoring (7)
1. individua il periodo esatto
2. distingue anagrafe e situazione sostanziale
3. verifica la causa della cancellazione
4. considera eventuale iscrizione altrove
5. verifica titolo di soggiorno e residenza legalmente rilevante
6. richiede documentazione
7. formula conclusione condizionata

### Error Taxonomy
- **EC1:** cancellazione anagrafica = perdita automatica del requisito
- **EC2:** cancellazione anagrafica irrilevante in assoluto
- **EC3:** mancata ricostruzione cronologica
- **EC4:** conclusione senza documentazione

### Struttura repository
/caso-3/ -> esempio pubblico
/images/ -> screenshot benchmark

### Licenza
MIT - Uso ricerca

### Contatti
Metodo sviluppato per portfolio AI Evaluation.
