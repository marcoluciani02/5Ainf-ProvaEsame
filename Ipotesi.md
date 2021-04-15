Si ipotizza che ogni piano ospiti 2 reparti ciascuno. Le stanze abbiano un range di pazienti che variano da 2 a 4. Si ipotizza che il server sia posizionato in una stanza chiusa all'interno di una stanza chiusa dell'ospedale e che le modifiche a tale server siano possibili solo tramite un host posizionato all'interno della stanza.

Ipotizzo che ogni reparto abbia al suo interno 10+ stanze. Comunque in numero non superiore alle 15 stanze.

Si ipotizza che ogni medico debba identificarsi all'accesso nella rete e anche nell' accesso al portale dell'ospedale tramite codice Medico e Password. Queste informazioni si ipotizzano siano racchiuse in una tabella separata dalla tabella medico all'interno del database. 

Si ipotizza che i dottori abbiano la facoltà di accedere a siti preventivamente autorizzati nella progettazione e che tali siti possono essere aggiunti o modificati solo dall'amministratore di rete tramite l'host collegato direttamente al server. Tale host non deve essere accessibile dal resto degli host della rete.

La rete pubblica dell'ospedale deve essere indipendente dalla rete sulla quale si collegano i medici. 

I collegamenti avverrano tramite cavo lan fino agli acess point distribuiti all'interno dei reparti.

La connessione con i tablet verrà eseguita in wireless. Alla rete potranno collegarsi solo i dispositivi in il quale mac address è stato autorizzato.

I dottori non potranno eseguire modifiche strutturali alla configurazione di rete, del server e del database, tale mansione è riservata all'amministratore di rete.

I Medici saranno differenziati in dottori e infermieri. Tra le due categorie ci sarà differenza sulle possibilità di modifica al database. 

Si ipotizza che la rete sia protetta da nat e firewall. Sarà possibile interagire sia in inbound che in outbound solo con i siti autorizzati e solo tramite protocollo https. 

Si ipotizza che la configurazione della rete sia a stella estesa.

Resta da stabilire la modalità di autenticazione di accesso alla rete da parte dei medici.

Sul server si ipotizza sia presente un indirizzo apparte per la farmacia per la gestione delle richieste. La farmacia non avrà accesso alla inserimento dei dati all'interno del database ma si limiterà a visualizzare le richieste e confermare l'invio dei medici richiesti o inserirne un commento in caso di assenza del farmaco.

Si ipotizza che la lunghezza massima del cavo lan tra il router e gli switch, tra due witch, tra uno switch e gli access point non possa superare la lunghezza di 50 per non avere perdite di segnale e di dati.
