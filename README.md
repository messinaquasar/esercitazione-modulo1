# esercitazione-modulo1

## Consegna
Creare un gioco in terza persona su Unreal Engine nel quale
Il gioco è composto da un unico corridoio (non necessariamente dritto) nel quale il giocatore principale deve correre evitando delle “trappole”. 
L’obiettivo del gioco è arrivare al termine del corridoio nel minor tempo possibile senza morire.
Un print indicherà il passaggio di ogni secondo di gioco e determinerà quindi il punteggio finale del giocatore

<br></br>
Il gioco prevede quindi:
- un <b>personaggio</b> in terza persona 
  - capace di correre, sprintare, saltare
  - che possiede una sua health (printare il suo valore quando viene modificato)
- un <b>sistema di hazard ambientali</b> (“interagibili) che sottraggono vita al giocatore quando finisce sopra di essi 
  - l’interazione avviene all’overlap con il volume dell’interagibile
- un <b>timer</b> che scorre e che stampa il tempo di gioco
- un <b>corridoio</b> (a piacimento) nel quale sono piazzati gli hazard ambientali
- un <b>trigger iniziale</b> che fa partire il timer di gioco e un <b>trigger finale</b> che stoppa il timer indicando il tempo totale di gioco (fine del gioco)

<br></br>
Altri requisiti:
- rispettare i principi della programmazione orientata agli oggetti (classi, attributi, metodi, incapsulamento, ereditarietà) durante l’implementazione
- consegnare una build
va pushata nella repository https://github.com/messinaquasar/esercitazione-modulo1 dentro la cartella builds
  - zippare la cartella windowsNoEditor della build e rinominarla con la seguente nomenclatura: CognomeNome

