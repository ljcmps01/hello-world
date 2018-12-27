$cd NombreDeLaCarpeta				Mueve la ventana de comando a la direccion escrita
$ls						Muestra el contenido de la carpeta
$cd						Te lleva al directorio inicial
$mkdir NombreDeLaCarpeta			Crea una carpeta en el directorio


$git init					Inicializacion de Git
$git clone Direccion/Del/Repositorio		Clona el repositorio completo en el directorio seleccionado
$git remote add origin LinkRepositorioGitHub	Conecta el repositorio de GitHub con el directorio en el que se encuentra
						La ventana de comandos
$touch	NombreDelArchivo			Crea un nuevo Archivo
$git add NombreDelArchivo			Prepara un archivo para que sea agregado al repositorio de Git
$git add .					Prepara para agregar a todos los archivos en el directorio
$git commit -m "Descripcion"			Crea una nueva version del directorio
$git status					Te muestra el status del repositorio (modificaciones o archivos nuevos)
$git push origin Master/NombreDeLaRama		Manda el nuevo archivo a la rama seleccionada

$git branch NombreDeLaRama			Crea diversas ramas de un mismo repositorio
$git checkout NombreDeLaRama			Te lleva a la rama mencionada
$git merge NombreDeLaMezcla			Mezcla un par de ramas creadas anteriormente
$git rebase NombreDeLaRamaPrincipal		Copia todas las ramas como siguientes a la rama mencionada