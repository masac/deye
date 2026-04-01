Tip integrare Home Assitant: HACS - Solarman Stick Logger v26.08.16

1) Fisierul configuration.yaml se adauga in folderul homeassitant. In el sunt setarile pentru ca home assistant sa calculeze timpul estimativ de descarcare al baterie pana la 30% sau de incarcare pana la 100%.

2) In Panou setari invertor Deye este codul ce trebuie inserat pentru a obtine imaginea de mai jos.


<img width="349" height="410" alt="imagine" src="https://github.com/user-attachments/assets/973120d3-b09f-4cb7-876d-0f783f315c5c" />


3) Cea mai frecventa problema o reprezinta varfurile de tensiune care fac ca invertorul sa se opreasca cand se atinge tensiunea de 253 V.
   Solutia gasita: In System Work Mode la invertor, la Max Sell Power se seteaza initial 2000 W si se creste gradual valoarea cat permite reteaua. 
