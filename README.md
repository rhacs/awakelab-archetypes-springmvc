![GitHub contributors](https://img.shields.io/github/contributors/rhacs/awakelab-archetypes-springmvc?style=flat-square) ![GitHub top language](https://img.shields.io/github/languages/top/rhacs/awakelab-archetypes-springmvc?style=flat-square) ![GitHub last commit](https://img.shields.io/github/last-commit/rhacs/awakelab-archetypes-springmvc?style=flat-square) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/rhacs/awakelab-archetypes-springmvc?style=flat-square) ![GitHub](https://img.shields.io/github/license/rhacs/awakelab-archetypes-springmvc?style=flat-square) [![Maven Central](https://img.shields.io/maven-central/v/io.github.rhacs/awakelab-archetypes-springmvc?style=flat-square)](https://search.maven.org/search?q=g:%22io.github.rhacs%22%20AND%20a:%22awakelab-archetypes-springmvc%22)

# awakelab-archetypes-springmvc
Arquetipo para la generación de proyectos simples en Maven bajo SpringMVC

## Dependencias
 * Spring Framework Context v5.2.7
 * Spring Framework WebMVC v5.2.7
 * Java Servlet API v4.0.1
 * JavaServer Pages API v2.3.3
 * JavaServer Pages Standard Tag Library (JSTL) v1.2
 * JUnit Jupiter API v5.6.2

## Creación del Proyecto

```bash
mvn archetype:generate -DarchetypeGroupId=io.github.rhacs \
    -DarchetypeArtifactId=awakelab-archetype-springmvc \
    -DarchetypeVersion=1.0.6\
    -DgroupId=<el GroupID de tu Proyecto> \
    -DartifactId=<el ArtifactId de tu Proyecto>
```

Siendo:
 * **-DgroupId=** el nombre del paquete para tu proyecto
 * **-DartifactId=** el nombre de tu proyecto

Por ejemplo

```bash
mvn archetype:generate -DarchetypeGroupId=io.github.rhacs \
    -DarchetypeArtifactId=awakelab-archetype-springmvc \
    -DarchetypeVersion=1.0.6\
    -DgroupId=cl.rhacs.awakelab \
    -DartifactId=accidentabilidad
```
