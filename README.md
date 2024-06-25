# GNS3_practica
 Translatare activități Packet Tracer într-un environment GNS3


 # 17.06.2024
 Am modificat README


modificare noua

# 18.06.2024
Am instalat GNS3 impreuna cu GNS3 VM pentru o utilizare mai eficienta a resurselor hardware, cat si pentru a rula anumite tipuri de imagini de routere si switch-uri, cum ar fi cele de la Cisco IOS. 

Am creat prima topologie de retea, pe care am incarcat-o cu numele "BasicPingTestNetwork" in care am reusit sa atribui adrese ip pc-urilor, sa ma familiarizez cu mediu de lucru si cu modurile de configurare ale unei retele basic. 

Am inceput modulul de CCNA1, pentru o intelegere mai in profunzime a functionarii retelelor de calculatoare.

Urmeaza a reusi a descarca imagini pentru switch-uri cu management pentru a putea emula retele mai complexe.

# 19.06.2024
M-am documentat mai bine si am vazut ca e recomandat VMware Workstation Pro in loc de VirtualBox pentru ca este mult mai stabil, avand mai putine probleme de compatibilitate si erori de functionare. Drept urmare, am instalat si configurat VMware Workstation Pro, unde am importat GNS3 VM. 

Am incercat sa realizez retele mai complexe, dar switch-urile puse la dispozitie de GNS3 nu au accesibila consola, astfel ca a urmat o lunga cautare de tutoriale si site-uri de descarcari de image-uri compatibile. 
Am reusit in final sa gasesc site-ul https://techemergente.blogspot.com/p/ccnp.html pentru descarcari gratuite, dar n-am rezolvat inca sa importez in GNS3. 

Plan de implementare al proiectului:
  - Instalare si configurare initiala
    - descarcare imagini necesare 
  - Retea de testare simpla
    - configurare adresa IP pentru dispozitivele din retea
  - Retea de testare complexa
    - creare si configurare VLAN-uri
    - testarea comunicatiei intre dispozitivele din acelasi VLAN
  - Documentare si validare
  - Concluzii
    - analizarea procesului de migrare a configuratiilor din Packet Tracer in GNS3
    - notarea provocarilor intampinate si solutiile aplicate



# 20.06.2024
Am reusit sa descarc un sw Cisco si sa il configurez astfel incat sa imi booteze. In continuare am facut o topologie de retea in care am reusit sa dau ping intre 
pc-uri si switch, mai multe detalii am lasat in documentatia retelei.

# 21.06.2024
Am dezvoltat reteaua anterioara(configurareSwVLAN) si am separat reteaua in vlan-uri. Am configurat corespunzator, dar nu am reusit sa ma conectez remote de la un pc la sw,
deoarece vpcs-urile implicite de la GNS3 nu au functie de telnet sau ssh. Urmeaza a rezolva aceasta provocare.

# 25.06.2024
Am reusit sa imi conectez propriul laptop prin ssh la switch-urile din topologie. Am dezvoltat mai mult in documentatie.