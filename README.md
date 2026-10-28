# Procedure-di-Utilizzo-Sicuro-di-GitHub
Supporto ai Controlli ISO 27001 per lo Sviluppo Software

1.Scopo 
- Lo scopo principale e definire le regole delle procedure per l'utilizzo di GitHub durante le attività di sviluppo software, facendo cosi saremo sicuri di garantire sicurezza al codice sorgente, la tracciabilità delle modifiche e le conformità dei requisiti di ISO 27001.

2.Gestione degli Accessi
- L'accesso alle repository lo potranno effettuare solamente le persone che sono autorizzate.
- Gli utenti all'interno della repository dovranno utilizzare per forza l'autenticazione ai due fattori (MFA).
- Gli accessi che si effettueranno dovranno essere revisionati periodicamente.
- Gli account che non saranno più necessari per la repository, dovranno essere rimossi al più presto.

3.Gestione dei Repository
-I repository che contengono dei codici o delle informazioni private della azienda dovranno avere degli accessi limitati.
-Ogni repository dovrà avere un responsabile identificato per controllare sempre al più presto quando ci sono problemi.
-Le autorizzazioni dovranno essere assegnate secondo i principi dei minimi privilegi.

4.Sviluppo Sicuro
-La cosa migliore da non fare è inserire password, token, chiavi AP o altre credenziali all'interno dei repository.
-Le configurazioni meno sensibili devono essere gestite e protette con dei sistemi dedicati.
-Il codice dovrà rispettare tutte le linee guida del Secure Coding aziendale.

5.Gestione delle modifiche
-Le modifiche dovranno essere sempre effettuate tramite dei branch dedicati.
-Ogni modifica effettuata dovrà essere registrata tramite dei commit descrittivi.
-Le modifiche rilevanti dovranno essere sottoposte a dei Pull Request.

6.Revisione del Codice
-Prima di inserirlo ufficialmente, dovrà essere verificato da una secondo soggetto autorizzato.
-Eventuali problematiche o vulnerabilità dovranno sistemate prima rilascio.

7.Gestione delle Vulnerabilità
-Dovranno essere effettuati dei controlli periodici sulla dipendenza del software.
-Le vulnerabilità identificate dovranno essere analizzate e gestite secondo le regole date.

8.Backup e Continuità Operativa
-I repository dovranno essere inclusi nei processi di backup della azienda.
-Dovranno essere previste delle procedure di recupero in caso di perdita di dati.

9.Tracciabilità
L'organizzazione dovrà poter effettuare:
-Chi ha effettuato le modifiche;
-Quando è stata effettuata la modifica;
-Con quale versione del software viene rilasciata;

10. Verifiche Periodiche
Almeno una volta all'anno dovranno essere verificati:
-Autorizzazioni degli utenti;
-Configurazioni di sicurezza;
-Rispetto delle procedure date;
-Eventuali vulnerabilità aperte;
