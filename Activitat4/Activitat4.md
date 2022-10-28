# Activitat 4
## Gestió d'usuaris

Hi ha dos tipus d'usuaris, els admins amb permissos per gestionar Owncloud i els usuaris normals.

On fica resposta afegeix una captura de pantalla on es vegi que has fet l'acció que es demana.

Aquesta part de la pràctica la feu amb un company/a, li creeu un usuari i li doneu el vostre nom de domini d'Owncloud.

Per a que pugui accedir necessitarà:

- La MV amb owncloud ha d'estar en mode "adaptador pont".
- El fitxer /etc/hosts del company ha de tenir la IP de la MV i el nom de domini de la MV del company/a.

4.1.- Crea un usuari admin que es digui adminXYZ, on XYZ són les inicials del teu nom:

![](fotos/001.png)

4.2.- Inicia sessió com a l'usuari adminXYZ.

![](fotos/002.png) ![](fotos/003.png)

4.3.- Crea un usuari XYZ on XYZ son les inicials del company/a i afegeix-lo al grup usuaris, aquest usuari tindrà una quota de 512 MB.

![](fotos/004.png)

4.4.- Podem crear fitxers d'una mida determinada a Linux amb la comanda:

```sh
truncate -s 10M file.txt
```

A l'exemple es crea un fitxer de 10MB.

Crea 6 fitxers de 100MB i pujal's a Owncloud un per un.

![](fotos/005.png)

4.5.- Mostra el missatge d'error per haver superat la quota d'usuari.

![](fotos/006.png)

4.6.- Busca al teu perfil quin percentatge de quota estas utilitzant.

![](fotos/007.png)

4.7.- Canvia la quota de l'usuari a 1GB i mostra tots els fitxers pujats.

![](fotos/008.png)

4.8.- Crea un usuari anomenat usuari2XYZ i fical al grup usuaris.

![](fotos/009.png)

4.9.- Comparteix un fitxer de usuariXYZ a usuari2XYZ i mostra com l'usuari2XYZ pot veure i descarregar el fitxer.

![](fotos/010.png)

![](fotos/011.png)

![](fotos/012.png)


4.10.- Esborra la carpeta Learn more about owncloud.

![](fotos/013.png)


4.11.- Recupera la carpeta Learn more about owncloud.

![](fotos/014.png)

![](fotos/015.png)

4.12.- Com a usuariXYZ crea una carpeta nova anomenada shared i comparteix-la amb l'usuari usuari2XYZ.

![](fotos/016.png)

![](fotos/017.png)

4.13.- Entra a Market instal·la dues aplicacions que no estiguin ja instal·lades i explica què fan i com funcionen.

PRIMERA APP: Aquesta app ens proporciona un fondo de pantalla a l'hora d'iniciar sessió.

![](fotos/018.png) 

![](fotos/019.png)

SEGONA APP: Amb aquesta segona app, podem pujar arxius mp4 i escoltar musica desde el propi owncloud. Inclus podem escoltar la radio per internet.

![](fotos/020.png) 

![](fotos/021.png) 

![](fotos/022.png) 

4.14.- Crearem una carpeta nova per emmagatzematge a Owncloud, la carpeta serà /media/publicXYZ on XYZ són les teves inicials i apareixerà amb el nom de public als usuaris.

Aquesta carpeta haurà de pertànyer a l'usuari www-data.

RESPOSTA

4.15.- Connectarem la carpeta publicXYZ com emmagatzematge local, tal i com s'indica aquí. Tots els usuaris tindran accés a la carpeta.

RESPOSTA

4.16.- Un usuari normal pujarà un fitxer a la carpeta public.

RESPOSTA

OPCIONAL.- Aquesta tasca és opcional.

Intenta connectar com a emmagatzematge extern el teu compte de Google Drive de l'Institut. Tens com fer-ho aquí.

RESPOSTA