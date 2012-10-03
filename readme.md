#Questa è una patch di aggiornamento SOLO per la versione 1.5.0.#
È composta da una cartella di file da caricare + una patch SQL da lanciare.

##ATTENZIONE FARE BACK-UP COMPLETO FILE + DATABASE PRIMA DI PROCEDERE##

Applicando i file presenti in "root_zencart" in sovrascrittura nella root del Vs Zen Cart, dopo aver opportunamente rinominato la cartella "admin" con il nome che le avete assegnato online, sarà possibile aggiornare la versione 1.5.0 alla nuova 1.5.1 ITALIANA di Zen Cart® alla data 01/10/2012. Questo pacchetto non contiene la patch di conversione codifica in utf8 dei files di lingua italiana. Se non è stata applicata in precedenza la patch di codifica utf8, allora è preferibile aggiornare in altro modo: scaricando la patch di codifica, applicandola e poi applicando questo aggiornamento oppure scaricando il pacchetto che comprende sia la patch di codifica sia l'aggiornamento.  

Una volta caricati i file (attenzione ad evitare la possibile sovrascrittura dei file di lingua in /classic) è necessario da pannello di amministrazione in Strumenti > Installa patch SQL lanciare:
UPGRADE_mysql_ZC_da_150_a_151.sql

##ATTENZIONE FARE BACK-UP COMPLETO FILE + DATABASE PRIMA DI PROCEDERE##

Per webmaster / sviluppatori abbiamo inserito anche la cartella "zc_install" così da poter caricare e installare la vostra versione aggiornata 1.5.1. Per tutti gli altri è una cartella da NON caricare

Dettagliata lista modifiche e soluzione bug è disponibile in:
http://www.zen-cart.com/showthread.php?200259-Zen-Cart-v1-5-1-Released!-**-Performance-Improvements-Bug-Fixes-etc



