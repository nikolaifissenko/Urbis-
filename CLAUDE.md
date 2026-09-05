# Urbis — CLAUDE.md

Contesto per qualunque sessione (questa o una futura) che lavora su Urbis. Leggere prima di agire.

## Cos'è

Attività di servizi turistici ed esperienze a Roma, co-fondata da **Nikolai Fissenko Caballero** e **Valeria**. Stato: lancio lean in corso (settembre 2026) — si parte operativi sotto la partita IVA individuale di Valeria, **non** con una SRLS (che resta l'obiettivo quando l'attività sarà validata, vedi sotto).

Ruoli decisi:
- **Valeria** — amministrazione, contabilità/fatturazione (via la sua partita IVA e il suo commercialista), comunicazione.
- **Nikolai** — gestione operativa delle esperienze (ha esperienza diretta di tour a Roma), business manager della strategia complessiva.

Nikolai gestisce Urbis come business manager operativo — decisioni di prodotto, marketing, vendite, legale.

## Scelta strategica di fondo

Urbis vende **esperienze**, non **tour guidati**. Non è un dettaglio di marketing: è la scelta che determina se serve o no l'abilitazione nazionale di guida turistica (Legge 190/2023 — esame nazionale, Elenco Nazionale Guide Turistiche, in vigore dal 2026).

**La distinzione legale vera non è la parola usata nell'annuncio, è il contenuto dell'attività:**
- **Guida turistica (riservata, serve abilitazione)** = illustrazione e interpretazione del valore storico/artistico/culturale del patrimonio (musei, siti, centro storico) durante una visita.
- **Non riservato** = accompagnamento, logistica, guida del mezzo (golf cart), assistenza pratica, aneddoti generali — senza interpretazione strutturata del patrimonio culturale.

Quindi: chiamare l'offerta "esperienza" e non "tour" non basta da solo. Quello che l'host dice e fa durante il giro deve restare dal lato "accompagnamento/attività", non diventare una lezione di storia dell'arte. Dettagli in `legale/costituzione-e-licenze.md`.

## Prodotto (catalogo esperienze in definizione)

Non solo golf cart: Urbis vende esperienze turistiche a Roma in generale (culinarie, sightseeing leggero, attività locali) — vedi `business-plan/idee-esperienze.md` per la lista di opzioni allo studio. Il golf cart resta un candidato forte (Nikolai ha esperienza diretta), come attività (guida del mezzo, itinerario, assistenza), non come tour guidato d'arte/storia.

Il cliente esistente di golf cart tours di Nikolai (attività freelance separata, vedi repo `golf-cart-tours`) **non viene assorbito**: Urbis è un brand e un'attività nuova e distinta. Normativa golf cart specifica (SCIA, controlli GdF, omologazione veicoli) tenuta nel repo `golf-cart-tours` (`normativa-e-controlli.md`), perché riguarda anche quell'attività freelance, non solo Urbis — se/quando Urbis lancia un'esperienza in golf cart, consultare quel file.

## Struttura giuridica — fase attuale vs obiettivo

**Fase attuale (lancio lean, capitale ~zero):** si opera sotto la partita IVA individuale di Valeria, per non spendere in costituzione prima di aver validato la domanda. Attenzione: questo significa che **non c'è responsabilità limitata** — vedi `legale/accordo-soci-e-rischi.md`, è la parte più importante da capire prima di partire così.

**Obiettivo quando l'attività si valida:** trasformare in **SRLS** (SRL semplificata) con Nikolai e Valeria soci — capitale basso, costituzione economica, statuto standard per legge. Quote presumibilmente non 50/50 (Valeria conferirebbe più capitale) — con lo statuto standard SRLS le quote sono di norma proporzionali ai conferimenti. Limite noto della SRLS: statuto tipizzato, poco margine per patti particolari — se serve più flessibilità in futuro si trasforma in SRL ordinaria.

## File in questo repo

- `legale/costituzione-e-licenze.md` — analisi legale (guida turistica vs esperienza) + checklist costituzione SRLS (per quando si formalizza) + codici ATECO.
- `legale/agenzia-di-viaggio.md` — licenza di direttore tecnico di agenzia di viaggio (Regione Lazio) che sta prendendo Valeria, costi reali, quando serve davvero.
- `legale/accordo-soci-e-rischi.md` — rischio "società di fatto" nel lancio lean sotto la partita IVA di Valeria, e bozza di accordo scritto tra Nikolai e Valeria.
- `business-plan/piano-avvio.md` — piano d'avvio operativo, checklist, decisioni ancora aperte.
- `business-plan/idee-esperienze.md` — lista di idee di servizi/esperienze da offrire.

## Come lavorare su questo repo

- Nikolai non è tecnico su questo fronte quanto su StreetSmart: fare il lavoro (bozze di documenti, checklist, testi) piuttosto che dargli solo una lista di comandi.
- Chiedere solo l'informazione che solo lui (o Valeria) può dare — non richiedere conferme su cose deducibili dal contesto.
- Materia legale italiana: usare la skill `avocat` per rigore, citare sempre la base normativa, segnalare quando serve un notaio/commercialista/avvocato fisico.
