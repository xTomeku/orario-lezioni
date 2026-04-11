# Informativa sulla Privacy (Privacy Policy)

**Ultimo aggiornamento:** 11 Aprile 2026

L'applicazione **QuickCheck** (di seguito "l'App") è progettata per fornire agli studenti dell'Università del Salento un modo rapido e semplice per consultare gli orari delle lezioni, cercare in rubrica e gestire il proprio piano di studi.

Questa Informativa sulla Privacy spiega come l'App gestisce i dati.

## 1. Raccolta e Utilizzo delle Informazioni
L'App **non raccoglie, non memorizza e non trasmette** alcun dato personale identificabile (come nome, cognome, numero di telefono o indirizzo email personale) a server di terze parti o allo sviluppatore.

### Dati memorizzati sul dispositivo (Locale)
Tutte le preferenze e i dati selezionati dall'utente vengono memorizzati **esclusivamente sul dispositivo** dell'utente tramite tecnologie di persistenza locale (SharedPreferences e Hive). Questi dati includono:
- Corso di studi selezionato e relativo percorso (ID e nome).
- Elenco degli insegnamenti e materie preferite.
- Impostazioni dell'interfaccia (tema chiaro/scuro, lingua, modalità di visualizzazione).
- Cache degli orari scaricati (per consentire la consultazione offline).
- Stato del tutorial e messaggi di sistema letti.

Questi dati non lasciano mai il dispositivo dell'utente, a meno che l'utente non decida esplicitamente di esportare la propria configurazione manualmente.

## 2. Collegamenti a Servizi Esterni
Per funzionare correttamente, l'App comunica con i seguenti servizi esterni:

### Università del Salento (unisalento.it)
L'App scarica i dati pubblici relativi agli orari e alla rubrica direttamente dai server ufficiali dell'Ateneo:
- `logistica.unisalento.it`: Per il recupero degli orari delle lezioni e della disponibilità delle aule.
- `unisalento.it/rubrica`: Per la ricerca dei contatti dei docenti.

Queste richieste sono necessarie per fornire il contenuto dell'App. Nessun dato utente viene inviato a questi server, se non i parametri di ricerca necessari (es. il nome del corso o il nome del docente cercato).

### GitHub (github.com)
L'App contatta periodicamente un repository pubblico su GitHub per:
- Verificare la disponibilità di nuovi aggiornamenti (tramite un file JSON).
- Scaricare eventuali comunicazioni o messaggi tecnici importanti relativi al funzionamento dell'App.

## 3. Cookie e Tracciamento
L'App **non utilizza** cookie di profilazione, né strumenti di tracciamento o analisi (come Google Analytics, Firebase Analytics o simili). Non vengono visualizzati annunci pubblicitari (Ads).

## 4. Autorizzazioni Richieste
L'App richiede le seguenti autorizzazioni per scopi specifici e funzionali:
- **Accesso a Internet**: Necessario per scaricare gli orari, cercare i contatti in rubrica e verificare la disponibilità di aggiornamenti.
- **Installazione di pacchetti (REQUEST_INSTALL_PACKAGES)**: Poiché l'App gestisce un sistema di aggiornamento indipendente dagli store (tramite download diretto dal repository GitHub), richiede l'autorizzazione per installare nuovi pacchetti. Questa funzione viene attivata solo quando l'utente conferma esplicitamente di voler scaricare e installare una nuova versione di QuickCheck.
- **Accesso alla memoria (Storage)**: Su alcune versioni di Android, potrebbe essere necessario per salvare temporaneamente il file dell'aggiornamento (.apk) prima di procedere all'installazione.

## 5. Modifiche alla Privacy Policy
Potremmo aggiornare questa Informativa sulla Privacy di volta in volta. Ti consigliamo di consultare questa pagina periodicamente per eventuali modifiche. Le modifiche sono efficaci nel momento in cui vengono pubblicate.

## 6. Contatti
Per domande o chiarimenti riguardanti questa Informativa sulla Privacy, puoi contattare lo sviluppatore tramite il repository GitHub ufficiale del progetto.

---
*Questa Informativa è stata redatta in conformità con il principio di minimizzazione dei dati e trasparenza verso l'utente.*

