Administració de SistemesInformàtics en la Xarxa![](fotos/captura(1).png)

Desenvolupamentd’Aplicacions Multiplataforma

**M1** – Implantació de SistemesOperatius

**UF3** – Implantació de ProgramariEspecífic


*Yassin Bekkaoui*

*Axel Fernandez*

**Servidor d’Imatges**

1. Instal·lar i configurar un servidor FOG
2. Capturar des del client un Windows
3. Capturar des del client un Ubuntu
4. Instal·lar imatge Windows
5. Instal·lar imatge Ubuntu
6. Llençar un paquet per a que s’instal·li als clients

Instal·lem   la configuració en español 

![](fotos/captura(2).png)

Selecionem la segona opció.

![](fotos/captura(3).png)

Establim la configuració de red que usarem. ip estatica .

![](fotos/captura(4).png)












Comprovem la configuració.

![](fotos/captura(5).png)












Configurem el perfil del l’equip servidor: usuari servidor: contrasenya mireia

![](fotos/captura(6).png)











Reiniciem l’equip

![](fotos/captura(7).png)










Configurem un netplan  per a assegurar una correcta configuració de red

![](fotos/captura(8).png)

Comprovem que s'hagi aplicat lo netplan 

![](fotos/captura(9).png)



Instalem els arxius del fog

![](fotos/captura(10).png)

accedim al instalador i el llançem 

![](fotos/captura(11).png)

Crearem  la nostra configuració i una vegada acabada ens mostrarà el seleccionat

![](fotos/captura(12).png)








instal·lacio paquets necesaris

![](fotos/captura(13).png)
















` `A continuació ens demana que actualitzem entrant al següent link

![](fotos/captura(14).png)







Accedim desde el client i fem click a update

![](fotos/captura(15).png)














s’ens obrira aquesta finestra accedim i s’ens descargara automaticament 

![](fotos/captura(16).png)










Entrem novament al fog i podem veure com s’ja actualitzat i ens dona les credencials.

![](fotos/captura(17).png)

Accedim al enllaç

![](fotos/captura(18).png)



Comprovació desde client ubuntu 

![](fotos/captura(19).png)




Comprovació desde client windows 

![](fotos/captura(20).png)


















Crearem una imatge windows (no es una imatge com a si es on es guardara l’imatge)

![](fotos/captura(21).png)




Crearem una imatge ubuntu (no es una imatge com a si es on es guardara l’imatge)

![](fotos/captura(22).png)




Instalem aquest client al windows

![](fotos/captura(23).png)

![](fotos/captura(24).png)

![](fotos/captura(25).png)

anem a host  i vinculem la imatge de hosts 

![](fotos/captura(26).png)

accedim a task - basic task capture

![](fotos/captura(27).png)











Despres iniciem el windows per xarxa 

![](fotos/captura(28).png)












POdem veure com esta accedin al servidor per conexio 

![](fotos/captura(29).png)













Registrem l’equip

![](fotos/captura(30).png)









Realitza la clonaci de l’equip

![](fotos/captura(31).png)

\-










Crearem una nova maquina 

![](fotos/captura(32).png)










reguistrarem la maquina  

![](fotos/captura(33).png)







Selecionem que volem carregar un imatge.

![](fotos/captura(34).png)








Selecionem l’imatge anterior de windows

![](fotos/captura(35).png)








Ens demanara les credencials les introduim 

![](fotos/captura(36).png)










Seguidament comensara l’instalació

![](fotos/captura(37).png)












Quan acabe es reiniciara

![](fotos/captura(38).png)








llevem arranc de xarxa i establim l’arranc normal

![](fotos/captura(39).png)

\-


Accedim al nostre ubuntu i el registre amb el format lent   

![](fotos/captura(40).png)








Introduirem el nom del host i farem intros 

![](fotos/captura(41).png)

Anem a la pagina i podem veure que aqui tenim el host accedim dins 

![](fotos/captura(42).png)





i el vinculem amb l’imatge , tambe establirem el host Bios i efi  amb GRUB per al correcte funcionament

![](fotos/captura(43).png)





actualitzem i anem a tasques basiques i selecionem fotos/capturar 

![](fotos/captura(44).png)

Selecionem els següents parametres.

![](fotos/captura(45).png)

Accedim al ubuntu que fotos/capturarem i s’ens començara a clonar 

![](fotos/captura(46).png)











Una vegada acabat creem una nova maquin i  accedim al menu de carregar imatge

![](fotos/captura(47).png)

introduim les credencials 

![](fotos/captura(48).png)

Selecionem l’ubuntu

![](fotos/captura(49).png)








i comenzará el proces .

![](fotos/captura(50).png)














I en acabar wala ja tenim el nostre ubuntu perfectament equipat 

![](fotos/captura(51).png)

Escriurem el següent script per instal·lar google

![](fotos/captura(52).png)

anem a crear un nou snapin

![](fotos/captura(53).png)















aixi quedara

![](fotos/captura(54).png)

anem al host ubuntu : 

![](fotos/captura(55).png)

aquesta opcio

![](fotos/captura(56).png)

selecionem l’script

![](fotos/captura(57).png)




