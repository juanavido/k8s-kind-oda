# Gestión de Clúster KIND con `cluster.sh`

Este proyecto incluye el script `cluster.sh` para facilitar la administración de un clúster Kubernetes local usando [KIND](https://kind.sigs.k8s.io/).

## Uso

```sh
./cluster.sh [comando]
```

### Comandos disponibles

- `create`  
  Crea un nuevo clúster KIND con la configuración definida en el proyecto.

- `delete`  
  Elimina el clúster KIND existente.

- `status`  
  Muestra el estado actual del clúster KIND.

- `load-images`  
  Carga imágenes Docker locales en el clúster KIND.

- `help`  
  Muestra la ayuda y los comandos disponibles.

## Ejemplo

```sh
./cluster.sh create
./cluster.sh status
./cluster.sh load-images
./cluster.sh delete
```

> **Nota:** Asegúrate de tener instalado [KIND](https://kind.sigs.k8s.io/) y Docker antes de ejecutar el script.
