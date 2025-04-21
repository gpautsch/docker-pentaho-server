# Docker Pentaho BBII Server 9.4

Repositorio oficial de la práctica de la cátedra Paradigmas y Lenguajes de Programación, de la Lic. en Sistemas de Información de la Universidad Nacional de Misiones.

## Equipo de cátedra

| Cargo                               | Nombre                              |
| ----------------------------------- | ----------------------------------- |
| Responsable de Teoria               | Dra. Nora Reyes                     |
| Responsable de Práctica             | Mgter. German Pautsch               |

## Administrador del Repo

Mgter. J. Germán A. PAUTSCH
[Aboutme](https://about.me/german.pautsch)

## Preparando el entorno

[guia para preparar el entorno](./entorno.md)

**Crear la imagen**
Una vez clonado este repositorio deberá:
- Descargar la versión 8 del JDK de Oracle y asegurate que poseá este nombre: *jdk-8-linux-x64.tar.gz* cuando lo descargues, se puede encontrar [aquí](https://www.oracle.com/java/technologies/javase/javase8u211-later-archive-downloads.html), también [aquí](https://gist.github.com/hgomez/9650687) hay una serie de comandos para descargarlo con wget, por ejemplo.
> wget https://github.com/frekele/oracle-java/releases/download/8u201-b09/jdk-8u201-linux-x64.tar.gz -O jdk-8-linux-x64.tar.gz 
- Descargar Pentaho Server CE, asegurate que posea el nombre *pentaho-server-ce.zip* cuando lo descargues, puedes utilizar este [enlace](https://drive.google.com/file/d/1VjvizNUY4aHvPt744u04iiP1S0wdmlxs/view?usp=sharing).
  
- Tambien utiliaremos Saiku que es una herramienta para navegar entre los datos y representarlos gráficamente. Puedes descargarla desde [aquí](https://drive.google.com/file/d/1Z5Ek3P4E3RFfcDr1sUFXZ0cNTTkod7xA/view?usp=sharing).

## Correr los container de la raiz

en una terminal desde la raiz de este repo ejecutar:

```bash
# para levantar los containers
$ docker-compose up

# para parar los containers
docker-compose stop
```Finalmente podrás disfrutar de tu Pentaho server accediendo a la url: *http://localhost:8080/pentaho* 

