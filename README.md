# Configuración Helm para base de datos MongoDB

Este repositorio contiene:

- Un archivo de valores de Helm para desplegar una base de datos **MongoDB** en OpenShift.
- Un flujo de **CI/CD en GitHub Actions** que aplica automáticamente el despliegue al clúster.

## Estructura del repositorio

```bash
.
├── helm/
│   └── values.yml       # Configuración de la release de MongoDB
└── .github/
    └── workflows/
        └── image-database-ci.yml   # Pipeline de CI/CD para desplegar en OpenShift