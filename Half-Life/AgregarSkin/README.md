# Agregar Skins de players  
1. Descargo los skins de [gamebanana](https://gamebanana.com/skins/cats/465 "Descárgalo de aquí papu")  
	![](.img/1.png)   
2. Escogeré el de [Vegeta](https://gamebanana.com/skins/178738 "Descárgalo de aquí")    
	![](.img/2.png)   
	![](.img/3.png)   
	![](.img/4.png)   
3. Obtengo esto:     
	![](.img/5.png)   
4. Descomprimo  
	```
	$ unzip svegeta.zip -d svegeta 
	```
	Este es el contenido de la carpeta "**svegeta**"  
	```
	svegeta
	├── dragonballzmapmodelpack.txt
	├── svegeta.bmp
	└── svegeta.mdl
	```
	La rama de directorios del juego que está instalado en nuestra computadora, en mi caso con Sistema operativo Debian:
	```
	.wine
	└── drive_c
	    └── Program Files (x86)
		└── Counter-Strike 1.6
		    └── valve
		        └── models
			    └── player
	```
5. Copiamos la carpeta "**svegeta**" dentro de la carpeta "**player**" que está dentro del juego  
	```
	$ cd ~/Downloads
	$ cp -r svegeta ~/.wine/drive_c/Program\ Files\ \(x86\)/Counter-Strike\ 1.6/valve/models/player
	```
	Y lo tendremos junto a los otros skins de personajes  
	![](.img/6.png)  
6. Vamos a verificar que podemos usar ese skin  
	![](.img/7.png)  
	![](.img/8.png)  
	![](.img/9.png)  
	![](.img/10.png)  
	![](.img/11.png)  
	![](.img/12.png)  
	![](.img/13.png)  
