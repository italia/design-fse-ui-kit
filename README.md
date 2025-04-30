# Fascicolo Sanitario Elettronico – prototipi

[![License](https://img.shields.io/github/license/italia/design-ui-kit.svg)](https://github.com/italia/design-ui-kit/blob/main/LICENSE)
[![Join the #design channel](https://img.shields.io/badge/Slack%20channel-%23design-blue.svg)](https://developersitalia.slack.com/messages/C7VPAUVB3/)
[![Get invited](https://slack.developers.italia.it/badge.svg)](https://slack.developers.italia.it/)

## Descrizione

Questo repository contiene i file dei **prototipi** del Fascicolo Sanitario Elettronico, con relativo **UI Kit del Fascicolo Sanitario Elettronico** realizzato per la progettazione delle schermate.

Il repository contiene le seguenti risorse:
- **UI Kit del Fascicolo Sanitario Elettronico** (`FSE-Libreria-componenti`);
- **FSE - Prototipo di base** (`FSE-Prototipo-di-base`);
- **FSE - Gestione dei consensi** (`FSE-Gestione-dei-consensi`);
- **FSE - Servizio di gestione richieste** (`FSE-Servizio-di-gestione-richieste`);
- **FSE - Servizio di visualizzazione campagne di screening e prevenzione** (`FSE-Campagne-di-screening-e-prevenzione`);
- **FSE - Servizio la mia storia clinica** (`FSE-Servizio-la-mia-storia-clinica`);
- **FSE - Servizio per la visualizzazione delle deleghe** (`FSE-Servizio-per-la-visualizzazione-delle-deleghe`).
- **FSE - Servizi per i miei percorsi di cura** (`FSE-Servizi-per-i-miei-percorsi-di-cura´);
- **FSE - Gestione del taccuino personale** (`FSE-Gestione-del-taccuino-personale`);
- **FSE - Servizi di patient empowerment** (`FSE-Servizi-di-patient-empowerment`);
- **FSE - Servizi di variazione della posizione del cittadino rispetto al SSN** (`FSE-Servizi-di-variazione-della-posizione-del-cittadino-rispetto-al-SSN`).

Questi file, disponibili sia per Figma e Sketch, forniscono un quadro chiaro di come dovrebbe apparire e funzionare il sito web del Fascicolo Sanitario Elettronico e le relative funzionalità.

Attenzione: alcune funzionalità presenti nei file Figma (.fig) potrebbero non essere presenti e/o non corrette nei file .sketch convertiti utilizzando la versione più recente di [fig2sketch](https://github.com/sketch-hq/fig2sketch). È consigliato pertanto controllare sempre il risultato della conversione e dichiarare lo stato delle risorse e questa eventualità agli utenti.

## Come iniziare

Scarica l'ultima versione disponibile nella pagina [Releases](https://github.com/italia/design-fse-ui-kit/releases). Ogni rilascio include i file sia per Figma che per Sketch.

Scarica inoltre la **[versione 3.6.3 di UI Kit Italia](https://github.com/italia/design-ui-kit/releases/tag/v3.6.3)**.  

Una volta scaricati, potrai aprire i file con i rispettivi programmi di progettazione e iniziare a esplorare le risorse.

### Collegamento delle librerie (UI Kit) ai prototipi in Figma

I prototipi utilizzano componenti collegati a **UI Kit del Fascicolo Sanitario Elettronico** (`FSE-Libreria-componenti`) e alla **versione 3.6.3** di UI Kit Italia (`UI-Kit-Italia`), che include icone, tipografia, colori e ombre applicati.

**Per collegare le librerie in Figma:**
1. Assicurati di disporre di un **account Figma Pro** o superiore, necessario per pubblicare e collegare le librerie.
2. Scarica le librerie `UI-Kit-Italia` e `FSE-Libreria-componenti` e i file dei prototipi come descritto nel paragrafo Come iniziare. 
3. Carica tutti i file nel tuo spazio di lavoro su Figma.
4. Pubblica le librerie `UI-Kit-Italia` e `FSE-Libreria-componenti` nel tuo spazio di lavoro su Figma seguendo la guida ufficiale: 
  - [Pubblica una libreria in Figma](https://help.figma.com/hc/en-us/articles/360025508373-Publish-a-library)
5. In `FSE-Libreria-componenti`, effettua lo "swap" dei componenti e stili mancanti ("Missing libraries") con quelli di `UI-Kit-Italia` seguendo la guida ufficiale: 
  - [Swap di una libreria su Figma](https://help.figma.com/hc/en-us/articles/4404856784663-Swap-style-and-component-libraries)
6. Pubblica gli aggiornmenti della libreria `FSE-Libreria-componenti`.
7. Dentro al file di ciascun prototipo, seguendo la stessa procedura, effettua lo swap dei componenti e stili mancanti con quelli di `FSE-Libreria-componenti` e `UI-Kit-Italia`.
8. Aggiungi i file `FSE-Libreria-componenti` e `UI Kit Italia` come librerie seguendo la guida ufficiale:
  - [Aggiungere una libreria in Figma](https://help.figma.com/hc/en-us/articles/1500008731201-Enable-or-disable-a-library-in-a-design-file)

**Nota per gli account Figma gratuiti:**
- Con un account Figma gratuito, non è possibile collegare le librerie direttamente. Tuttavia, puoi accedere agli elementi aprendo i file `FSE-Libreria-componenti` e `UI-Kit-Italia` e copiando manualmente i componenti nel tuo progetto.
