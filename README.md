# S I S C K O User Recon

**S I S C K O User Recon** es un script diseñado para buscar y verificar la disponibilidad de un nombre de usuario en diversas plataformas sociales y redes de citas. Es ideal para investigadores de seguridad, administradores de sistemas, o cualquier persona interesada en rastrear la presencia de un nombre de usuario en la web.

## Características

- **Búsqueda en múltiples plataformas**:
  - GitHub
  - Twitter
  - Instagram
  - Facebook
  - Tinder
  - Bumble
  - OkCupid
- **Exportación de resultados**:
  - Guarda los resultados de la búsqueda en un archivo de texto.
- **Comando de ayuda**:
  - Muestra una guía rápida de uso.
- **Compatibilidad**:
  - Fácil de ejecutar en entornos como Termux o cualquier sistema basado en UNIX/Linux.

## Instalación

### Requisitos

- Un sistema basado en UNIX/Linux (incluyendo Termux en Android).
- `curl` debe estar instalado (generalmente preinstalado en muchos sistemas).

### Clonación del Repositorio

Clona este repositorio en tu máquina o dispositivo:

```bash
git clone https://github.com/tu_usuario/SISCKO-User-Recon.git

**Navega al directorio del proyecto:**

cd SISCKO-User-ReconDale

**permisos de ejecución al script:**

chmod +x recon.sh

### USO 
- Búsqueda de un Nombre de Usuario
- Para realizar una búsqueda de un nombre de usuario en las plataformas configuradas:

./recon.sh nombre_de_usuario
