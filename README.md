# Apunts_UF_1
# Elementos del desarrollo de software
## Introducció
### Tipos de software
- **De sistema**: Sistemes operatius, controladors etc Aquell programari que gestiona el maquinari. 
- **D'aplicació:** Tots aquells programes que te una finalidad de facilitar una tasca, navegadors, processadors de text etc.
- **De desenvolupament:** Tot el programari que fem servir per desenvolupar els programes (interprets, compiladors, editors etc.)
### Relació hardware-software
- **Disc dur:** Guarda de manera permanent els arxius executables y les dades d'aquests. 
- **Memoria RAM:** Guarda de manera temporal el codi binari dels arxius executables i els arxius de dades en us. 
- **CPU:** Llegeix i executa les instruccions i els arxius guardats en la memoria RAM (Random Acces Memory)
- **E/S:** Recull noves dades desde l'entrada, es mostren els resultats, es llegeixen/guarden al disc..
### Codis font, objecte y executable
- **Codi font:** Arxiu de text llegible, escrit en un llenguatge de programació 
- **Codi objecte:** Arxiu binari no executable (un arxiu intermedi)
- **Codi ejecutable:** Un arxiu binari executable.

## Ciclo de vida del software
### Engineyeria de software
- Es la disciplina que estudia els principis i les metodologies per el desenvolupament i manteniment del programari i els sistemes.
### Fases principals del desenvolupament de software.
- **Analisis:**
 *És la fase en la qual es deteminen les necessitat que hem de cobrir amb el software a desenvolupar i els requists que ha de complir.*
- **L'especificació dels riquisits ha de:** 
  - Ser completa i sense omisions
  - Ser concisa
  - Evitar ambiguitats
  - Evitar  detalls de diseny o implementació
  - Ser entenible pel client
  - Separar requisits funcionals dels no funcionals
  - Dividir i jerarquitzar el model
  - Fixar criteris de validació
 

- **Diseny:**
  
  - Es descomposa i s'organitza el sistema en elements que poder ser desenvolupats per separat.
  - S'espeficifica la interrelació i funcionalitat dels elements per separat. 
  - **Les activitats habituals acostumen a ser:** 
   - Diseny arquitectònic
   - Deseny detallat
   - Diseny de dades
   - Diseny de interficie

- **Codificació:**
 - *S'escriu el codi font de cada component*
- **Proves:**
 - L'objectiu principal de les proves ha de ser fer fallar el programa per trobar errors i solucionar-los.
 - S'ha de maximitzar l'exposicio del programa a situacions diferents que poden provocar errors. 
- **Manteniment:**
  - Un cop el software ja està sent utilitzat, a vegaes pot donar-se el cas d'haver de modificar-lo en certes ocasions.
  - El tipu de manteniment pot ser:
  - **Corretiu:** Es corregeixen defectes.
  - **Perfectiu:** Millora la funcionalitat.
  - **Evolutiu:** Afegeix funcioanalitats.
  - **Adaptatiu:** Es fan modificacions per adaptar-lo a nous entorns.
- **Resultats que obtenim en cada fase.**
  - **Enginyeria de sistemes:** Especificació del sistema.
  - **Analisis:** Especificació de requisits de software.
  - **Diseny arquitectonic:** Un document que conté l'aquitectura del software.
  - **Diseny detallat:** Especificació dels moduls (els elements que formen el sistema)
  - **Codificació:** S'obté el codi font. 
  - **Proves d'unitats:** Un  cop acabat el procés s'obtenent els mòduls utilitzables. 
  - **Proves d'integració:** Es proven els moduls funcionant en conjunt i un cop finalitza aquest procés s'obté un sistema útil.
  - **Documentació:** Documentacio per l'usuari i pels tecnics i desenvolupadors involucrats.
  - **Manteniment:** Informes d'errors y un control dels canvis. 
## Models de desenvolupament de software.
- ### Models classics.
  - **Model en cascada:** És el model més antic, es compon de totes les fases de desenvolupament pero aquestes es porten a terme de manera ordenada. El resultat de cada fase serveix per iniciar la seguent. Al se tant sequencia, no es gaire flexible aixi que quan hi ha canvis d'especificacions, l'aplicació d'aquests canvis es molt lenta i tediosa. 
  - **Model en V:** Molt semblant al model en casacada, no obstant atribueix l'altura de la V als nivells d'abstracció, sent el nivell d'abstraccio mes alt el que correspon a les parts mes altes de la V. 
  - **Prototips:** A vegades els requisits no estan especificats clarament degut a manca d'experiencia previa, omisio o falta de concreció per part del client. Es a dir que el desenvolupador fa un prototip durant la fase d'analisis, aquest prototip es presentat al client i apartir d'aqui es modifica. Es pot repetir aquest procés molts cops fins que es dona amb el que vol el client/usuari. Hi ha dos tipus de prototip:
   - **Prototips rapids:** Es un prototip que nomes te el proposit de saber que vol el client i cop acabat es pot eliminar.
   - **Prototips evolutius:** Son prototips que es fan amb les mateixses eines i llenguatges que el producte final i pertant es fan sercir com a base per desenvolupar el projecte. 
   - **Model en espiral:** Desenvolupat per Boehm l'any 1998, es un model de desenvolupamnet que consisteix en fer que el proces passi per la comunicació amb el client, planificació, analisi de risc, enginyeria, construcció i adaptació i evalucio del client per cada fase. D'aquesta manera s'optimitza el temps ja que s'augmenta la participacio del client i pertant s'evita cometre errors que hagin de ser corregit de maneres poc convenients. 
### Metodologies àgils
  - Son metodes basats en el desenvolupament iteratiu incremental (Es consulta el client despres de qualsevol canvi)
  - Els requisits i les solucions evolucionen segons la necessitat-
  - La tasca la fa un equip auto-organitzat de persones de varies disciplines que participen en la presa de decisions de curt termini.
  -**Manifest per el desenvolupament agil:**
    - Valorar més als individus i les interaccions que els processos i eines
  - Les metodologies agils més conegudes:
    - **Kanban:** Inventat per l'enginyer de Toyota Taiichi Ohno durant els anys 40, es un sistema que atraves de targetes i pissares. Permet que tot el proces sigui controlat per la demanda a fi de fabricar el producte en el temps pertinent i en la quantitat justa. Busca donar el major valor possible al client amb el menor cost en recursos possible. 
    - **Scrum:** És un model de desdenvolupament incremental que consistexi en realizar iteracions periodiques en les que s'estableixe els objectius, i es realitza entrega parcial utilitzable pel clients. Es fan reunions diaries per controlar el proces. Hi ha tres rols principals, la veu del clients, el "Scrum Master" que s'encarrega que el proces vagi segons planificat i l'equip que es de entre 6 i 10 persones de diferentes disciplines que s'orgaitzen. En aquesta metodologia tambe tenim tres artefactes, una llista ordena dels requisits del producte, llista del requisits que es volen desenvolupar durant la iteració actual i l'increment que es el producte amb la millora afegida despres de cada sprint o iteració.
    -**XP (eXtreme Programming)**
    

  
   
  

  





























