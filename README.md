**Progetto Nicolas – Sito sulla Serie A**

Il progetto consiste nello sviluppo di un sito web informativo dedicato alla Serie A italiana.
L’utente può consultare informazioni su squadre, partite e classifiche.
L’intero progetto è disponibile nella cartella ProgWeb_2025_Nicolas_Prundis, che contiene anche il PDF con la proposta completa e le spiegazioni dettagliate.

**Introduzione**
Il sistema prevede due tipi di utenti: utente base e amministratore.

**Utente base:**
* Registrazione e login
* Possibilità di commentare gli articoli, modificarli o eliminarli
* Aggiungere la propria squadra preferita.

**Amministratore:**
* Registrazione e login
* Gestione completa dei commenti (modifica ed eliminazione)
* Possibilità di aggiungere, modificare ed eliminare marcatori.

**Struttura del Database**
Il database database_prundis è composto da 7 tabelle principali:
Utenti – gestione di profili e ruoli
Squadre – informazioni su squadre, città e stadi
Partite – risultati e giornate di campionato
Marcatori – statistiche sui gol
Commenti – commenti degli utenti su notizie e partite
Preferiti – collegamento tra utenti e squadre preferite
Notizie – articoli informativi.

**Avvio del Progetto (Guida Pratica)**
Database (MYSQL)
- Avvia MySQL
- Verifica il database_prundis
- Importa il file progettoPrundis.sql

Installazione
Apri il terminale nella cartella del progetto:
- npm install
- node server.js
- Verrà attivato il server su: http://localhost:3000

Una volta entrato nel browser puoi: 
- Visualizzare notizie e classifica
- Effettuare login/registrazione
- Interagire come utente o amministratore

