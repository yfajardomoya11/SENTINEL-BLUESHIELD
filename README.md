# Network Security & Backup Tool🛡️📡

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![Network](https://img.shields.io/badge/Role-Cybersecurity%20&%20Fiber%20Optic-blue?style=for-the-badge)

Este proyecto ha sido desarrollado por **Yananth Fajardo Moya** como una solución profesional para la gestión de infraestructuras críticas. Une el mundo de la **conectividad física (Fibra Óptica)** con la **seguridad lógica (Ciberseguridad)**.

## 🚀 Propósito del Proyecto
En entornos de red modernos, la configuración manual de dispositivos es propensa a errores humanos que pueden comprometer la seguridad. Este script automatiza el proceso de **Hardening** (endurecimiento de seguridad) y asegura la continuidad del negocio mediante **Backups preventivos** automáticos antes de cualquier modificación.

## ✨ Funcionalidades Clave
- **Gestión Masiva:** Procesa múltiples dispositivos (Routers/Switches) de forma simultánea desde un archivo de texto.
- **Respaldo Automático:** Genera una copia de la configuración actual (`running-config`) con fecha y hora antes de aplicar cambios.
- **Seguridad Capa 2/3:** - Desactiva protocolos inseguros (Telnet, HTTP).
    - Cifra contraseñas en texto plano.
    - Configura avisos legales (Banners MOTD).
    - Establece tiempos de espera de sesión (Exec-timeout).
- **Conexión Segura:** Utiliza exclusivamente el protocolo SSH para todas las interacciones.

## 🛠️ Estructura del Proyecto


```text
Network-Security-Automator/
├── backups/           # Carpeta de almacenamiento de respaldos
├── main.py            # Script principal de automatización
├── dispositivos.txt   # Listado de IPs de los equipos a configurar
├── requirements.txt   # Dependencias del proyecto (Netmiko)
└── README.md          # Documentación del proyecto
⚙️ Instalación y Uso
Clonar el repositorio:

Bash
git clone [https://github.com/yfajardomoya11/Network-Security-Automator.git](https://github.com/yfajardomoya11/Network-Security-Automator.git)
Instalar dependencias:

Bash
pip install -r requirements.txt
Configurar objetivos:
Añade las direcciones IP de tus dispositivos en el archivo dispositivos.txt (una por línea).

Ejecutar:

Bash
python main.py
⚠️ Disclaimer Ético
Este software se proporciona con fines educativos y de auditoría profesional. Como especialista en ciberseguridad, promuevo el uso responsable de estas herramientas. No me hago responsable por el uso indebido del código en infraestructuras sin la debida autorización técnica.

Contacto y Redes:

Nombre: Yananth Fajardo Moya

Especialidad: Técnico en Fibra Óptica | Estudiante de Ciberseguridad

GitHub: yfajardomoya11
## 🔗 Part of Cybersecurity Ecosystem

This project is part of a modular cybersecurity platform:

- Network Security Tool  
- Sentinel Watch  
- Guardian Engine  
