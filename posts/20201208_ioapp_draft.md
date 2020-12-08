## Il Bonus Mobilità

Anche il click-day per il Bonus Mobilità (3 Novembre 2020) ha fatto notizia per i disservizi associati: il sito del Ministero dell'Ambiente richiedeva la login tramite SPID, che in molti non riuscivano a completare per via di disservizi e rallentamenti dei vari provider (soprattutto Poste e Sielte). Una volta loggati, si veniva accolti da una sala d'attesa virtuale con migliaia di persone in coda, che ha ovviamente scatenato l'ironia delle persone.

La scelta di accodare gli utenti per evitare sovraccarichi non è esattamente quello che si intende per scalabilità; e la user experience in stile "Expo 2015" (ore di coda seguite da una visita veloce, in cui si cerca di capire qualcosa prima che ti sbattano fuori) sarà risultata scomoda a molti, che magari non avranno avuto la possibilità di ricollegarsi al momento esatto del loro turno. Ma almeno chi entrava riusciva ad usare il sito e a richiedere il bonus: ritentare un'operazione e trovarsi continuamente davanti a una pagina d'errore è sicuramente più frustrante di una coda virtuale.

Ma se l'ironia deli utenti si è scagliata sulla sala d'attesa virtuale, i problemi di SPID appiano sicuramente più preoccupanti. Un [articolo di Agenda Digitale](https://www.agendadigitale.eu/cittadinanza-digitale/perche-e-grave-il-crash-di-spid-e-del-bonus-bici-per-i-nostri-diritti/), oltre a chiedersi quale sia il senso del modello "click-day", pone l'accento sul tema del servizio pubblico:

> In particolare, gravissimo, è il fatto che vi siano stati notevoli disservizi da parte di alcuni identity provider SPID [...] Significa negare il diritto degli utenti a usare i servizi pubblici che richiedono Spid per l’accesso.

Insomma, non è solo il classico epic fail tecnologico della PA, ma si entra anche nel campo della lesione dei diritti dei cittadini; il Sole 24 Ore riporta ad esempio

> [...] il caso di una persona che non ha potuto accedere al proprio fascicolo sanitario elettronico (con Spid, appunto) per leggere il responso di un tampone covid. 

Essere performanti sotto picchi di carico vuol dire avere sistemi e applicazioni in grado di scalare, cioè gestire 10.000 utenti con la stessa rapidità con cui ne gestiscono 10. Scalare è difficile, ma non è impossibile: un grande aiuto l'hanno dato i provider di cloud computing, che permettono di avere un'infrastruttura che si adatti velocemente alle diverse esigenze, sostituendo lo scaling verticale a quello orizzontale. 

Ma per far scalare un sistema serve anche un'adeguata organizzazione del lavoro e cultura aziendale; se si progettano software con determinate best practice, e senza fare scorciatoie per arrivare in tempo alla data di consegna, è più facile risovere problemi di scalabilità. Far scalare un'applicazione, o un sistema distribuito, vuol dire eliminare i vari colli di bottiglia al suo interno, che si presentano di solito uno alla volta: ogni collo di bottiglia nasconde tutti quelli che possono esserci dopo di lui, fino a che non lo risolvi. Serve quindi un approccio iterativo, in cui per ogni problema comparso durante gli stress test o in produzione si ideino delle contromisure o dei miglioramenti.  

Ma non basta avere persone capaci, che sanno quello fanno: serve anche una leadership che condivida questi obiettivi, senza derubricarli a perdite di tempo. 

La situazione di solito è o bianca o nera: aziende più "antiquate" si portano dietro sia un'architettura lenta ad evolversi, dove aggiungere un nuovo server può richiedere mesi, sia un modo di lavorare poco flessibile, con rilasci semestrali ed un management il cui obiettivo è raggiungere le deadline concordate, piuttosto che assicurare la qualità del prodotto finale. Aziende più moderne sfruttano i benefici del cloud, hanno cicli di sviluppo brevi ed iterativi, e dei manager che si assumono la responsabilità di bucare una deadline se la qualità non è accettabile.

Migrare un'infrastruttura è complicato e costoso; cambiare i processi interni e "aggiornare" la propria cultura di lavoro lo è molto di più, se non proprio impossibile (forse ci sono riusciti solo i protagonisti di The Phoenix Project).



Ma se gli stress test sono inadeguati e mancanti, e se il pattern di traffico in produzione è un uso basso/moderato con solo 2 o 3 picchi all'anno durante i click day, risulta difficile migliorare velocemente, soprattutto se durante l'emergenza si è più impegnati a ristabilire la normalità che a capire quali siano i problemi di fondo.

E' anche vero che i click-day hanno sempre una data ben precisa, che permette a chi gestisce le infrastrutture di potenziarsi in anticipo; ci si aspetterebbe ad esempio che Poste Italiane, che gestisce circa l'80% delle identità SPID ed è quasi una società pubblica (è una Spa, ma controllata da Mef e Cdp), si faccia trovare preparata.

Intendiamoci, non è solo un problema di Spid: eventi come il Black Friday hanno sempre causato non pochi problemi anche ad ecommerce privati.


SPID nasceva come un servizio che i vari provider avrebbero potuto erogare a pagamento, dopo un primo periodo di X anni in cui sarebbe stato gratuito. Ma a Y 



Fonti 
1. https://www.agendadigitale.eu/cittadinanza-digitale/perche-e-grave-il-crash-di-spid-e-del-bonus-bici-per-i-nostri-diritti/
2. https://www.ilsole24ore.com/art/il-sistema-spid-mostra-suoi-limiti-identita-digitale-prova-sostenibilita-ADHZvd1?refresh_ce=1
