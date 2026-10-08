# Aplicación JavaFX · Gestor de gastos

Proyecto Maven que contiene la implementación del gestor de gastos de TDS. Reúne la interfaz gráfica, la lógica del dominio y la persistencia JSON.

## Organización

- `pom.xml`: configuración de Maven, Java 21, JavaFX 21 y Jackson.
- `src/main/java`: código Java y declaración del módulo.
- `src/main/resources`: recursos de la aplicación.
- `.idea` y `.settings`: configuración de los entornos de desarrollo presente en la entrega.

El punto de entrada configurado en Maven es `umu.tds.proyecto.App`.

## Ejecución

Desde esta carpeta, con JDK 21 y Maven:

```bash
mvn clean javafx:run
```

La aplicación permite gestionar gastos, consultar estadísticas, trabajar con grupos y configurar alertas. Para los pasos de uso y los formatos de importación, consulta el [manual de usuario](../docs/Manual%20de%20Usuario.md).

## Diseño y documentación

La [documentación técnica](../docs/documentacion.md) explica el modelo y las decisiones de diseño.

[Volver al repositorio](../README.md)
